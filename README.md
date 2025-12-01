Chestertown Bike Routes App:
A Flutter web application for creating, saving, and viewing custom bike routes around Chestertown.

App Overview:
This app allows users to tap points on a Google Map to create a bike route, enter route details, attach an image, and save the route locally using SharedPreferences. Users can then view all saved routes in a GridView layout and open any route in a dedicated view screen.

Screens Included
1. Main Map Screen
	•	Users tap on the map to add route points.
	•	Markers appear immediately and a connecting polyline updates in real time.
	•	Buttons allow clearing, undoing the last point, and saving the route.

2. Route Details Screen
	•	User provides a title and optional notes.
	•	Selects a route type (Road, Gravel, Scenic).
	•	Uploads an image from their computer.
	•	Preview of selected image appears before saving.

3. Saved Routes Grid Screen
	•	Displays all saved routes in a two-column GridView.
	•	Each tile shows a thumbnail (if available), route title, and number of points.
	•	Clicking any tile opens the detailed route viewer.

4. Route View Screen
	•	Shows the saved route on the map (left).
	•	Displays the saved photo inside a styled panel (right).
  •	Demonstrates final visual layout and map rendering.


Key Features Implemented:
- Route Type Selection
	•	Three radio button options: Road, Gravel, Scenic
	•	Saved and loaded with each route
	•	Helps categorize and organize routes

- Image Upload + Permanent Storage
	•	Users upload a photo from local files
	•	Photo preview shown in the details screen
	•	Saved as Base64 inside SharedPreferences
	•	Appears in the Saved Routes grid and route viewer

- Full Local Storage Support
	•	Saves all route data: title, notes, points, route type, and image
	•	Restores data automatically on app restart
	•	Works fully in Flutter web (using SharedPreferences)

- GridView Layout
	•	Replaced list UI with responsive tiles
	•	Provides a more visual and organized route list
	•	Each route tile is clickable and interactive

- Enhanced Route Viewer Layout
	•	Map on the left (main section)
	•	Image panel on the right (smaller section)
	•	Custom background color and border styling for the image area

Current State of the Application:
The app is fully functional for creating, saving, and viewing custom bike routes. It supports Google Maps route drawing, route details input, image uploads, and persistent data storage using SharedPreferences. All major UI features—GridView, navigation drawer, ThemeData styling, image previews, and route categorization—are complete. The app satisfies all course technical requirements and includes additional enhancements beyond what was required.

Future Plans (If More Times is Given):
If I continue working on this project, I would add:
	•	Current Location Button to automatically center the map on the user’s live position.
	•	Route Distance Calculator that computes total route distance in miles.
	•	Optional improvements like sorting/filtering routes, editing saved routes, or exporting routes.

GitHub Repository: https://github.com/raphaelsihoo/CSI210/tree/main/chestertown_bike 
