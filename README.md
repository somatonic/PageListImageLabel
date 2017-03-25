# Page List Image Label

This module enables you to show thumbnails of images from the pages in the admin page tree.

After installing you can define some options if you like to specify a width/height of the thumbnails and also change the look with some css options, like border padding and background color.

## How to use

The configuraton allows you to add a list of template along with the image field name you wish to output a thumbnail from.

It works for single, multiple and cropimage image field types. If multiple images field it will always take the first image from the stack.

Example:

`basic-page,image`

Would show a thumbnail for all pages that use `basic-page` template and have an image uploaded to the field `image`.

Or for croppable images you can define a crop setting (using dot notation):

`basic-page,image.landscape`

This will show the thumbnail you set in the croppable image with the name `landscape`.

