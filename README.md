Lower 48 Tracking Map
==============

This is a basic map and set of JSON files for tracking my family's visitation status of the lower 48. I'm thinking this might be a good template for others to track their visits, thinking if you went to Alaska and Hawaii, you'd remember it.

==== Plans ====
The plan for this repo is:
1. A basic map of the lower 48, showing the states and various visitation statuses for different family members. Interactivity will be limited to click or hover events for each state.
2. A relatively static legend showing how the different style colors translate to different visitations statuses
3. A TOC where the user can toggle different file overlays for different family members. This will require a differet JSON file for each family member. We'll probably need to duplicate the state geography in each JSON file, in order to effectively and quickly style the overlay according to the visitation status.

Several visitation statuses are tracked in a status column. These have two letter codes for simplicity in data:
1. NV: Not visited - red or pink
2. AT: Airport touchdown - yellow or orange
3. DT: Driven through - blue
4. OS: Overnight Stay - green

Each JSON file will also have a "last updated" column called "Update" that will contain the most recent year of status update.

=== Has ===
HTML file with basic map, light Mapbox style, and one GeoJSON overlay

=== Needs ===
Move the script to the js folder
Style the geojson based on status
Add more geojson layers