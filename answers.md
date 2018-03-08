1. Open Picture.java and look for the method getPixels2D. Is it there? 
The method isn't in the file, but it is created in zeroBlue with the this parameter since Picture extends simplePicture.

2. Open SimplePicture.java and look for the method getPixels2D. Is it there? 
Yes, we call it in the zeroBlue method is picture because it extends simple picture so there is no need to write the same method twice

3. Does the following code compile?     
DigitalPicture p = new DigitalPicture();
No Digital picture is not in the class or in the extended class.

4. Assuming that a no-argument constructor exists for SimplePicture, would the following code compile?        
DigitalPicture p = new SimplePicture();
Yes, picture extends SimplePicture so without a counstructor perameter it defaults to what the simplepicture has called.

5. Assuming that a no-argument constructor exists for Picture, does the following code compile?        
DigitalPicture p = new Picture(); 
This works since it is creating a picture class so it defaults to the class that it is in.

6. Assuming that a no-argument constructor exists for Picture, does the following code compile?        
SimplePicture p = new Picture();
Yes, there are defaults set to in the class

7. Assuming that a no-argument constructor exists for SimplePicture, does the following code compile?       
 Picture p = new SimplePicture();
 Not in picture since you can't upgrade the lower class of picture to a higher class of SimplePicture.
