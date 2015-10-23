Video Recorder
==============

iOS Project demonstrating how to capture video and play it back.

Upon launch you'll find two buttons: one to record media (right), and one to play the same file back. It's called video.mov and is saved in the app's Documents directory. 

Capturing happens with our old friend the UIImagePickerViewController which only accepts movie captures. The file is also saved to the Camera Roll.

Playback utilises an instance of MPMoviePlayerViewController.
