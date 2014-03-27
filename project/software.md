1. Run the following code on your Arduino:
    <%= knocker.ino =%>

2. While pressing the button, tap out a pattern onto the piezo. This records your secret knock.

3. Release the button and tap again; after tapping, wait a second. If the green light flashes quickly, the Arduino recognized your knock! If the red light flashes quickly, the Arduino decided that your knock did not match the secret knock.