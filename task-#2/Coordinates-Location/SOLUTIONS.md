1. Creating Directory: "mkdir Coordinate-Location"
   Entering Directory: cd Coordinate-Location
2. Creating North: mkdir North
 
	2.1 vi NDegree.txt
	    Enter 9
	    Ctrl+Shift+U + 00B0

	2.2 vi NMinutes.txt
	    Enter 5'

	2.3 vi NSeconds.txt
	    Enter 38"

	2.4 cat NDegree.txt NMinutes.txt NSeconds.txt > NorthCoordinate.txt

	2.5 Go to Coordinate-Location directory 
	    cp North/NorthCoordinate.txt North.txt
 
3. cd.. (x2)

4. Same steps as in 1. but changing names and values accordingly

5. Go to Coordinate-Location directory and type: cat North.txt East.txt > Location-Coordinates.txt  



 
