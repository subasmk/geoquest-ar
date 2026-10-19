# GeoQuest AR (demo)

Outdoor AR treasure hunt for school students. Team Techneon, expo demo.

Open `index.html` over HTTPS on an Android phone (Chrome). Allow camera, location and motion, go outside, tap **Play in AR**. Five treasures are hidden 10-28 m around where you start. Walk to one (within 5 m), answer the question, find all five.

**Practice mode** needs no GPS: joystick to walk, drag to turn. Use it indoors or as a backup at the expo.

Demo niceties: screen stays awake during play, fullscreen on start, sound effects (toggle in HUD), vibration on finds, GPS accuracy shown live, drag-to-look fallback when a phone gives no compass data, and the camera/GPS/motion switch off when the quest ends.

Free stack only: plain HTML/JS, phone GPS + compass + camera. Phone GPS is about 3-5 m accurate. A GNSS receiver with CORS data (paid) is the upgrade for centimetre accuracy.
