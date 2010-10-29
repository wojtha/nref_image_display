// $Id$

   =================================================================

         N O D E R E F E R E N C E   I M A G E  D I S P L A Y

   =================================================================

                ---  A Drupal CCK formatter module ---

_______________________________________________________________________________

   README
_______________________________________________________________________________

  This module is a CCK formatter for nodereference nodes. Supports ImageCache
  presets, Lightbox2 and Colorbox module.

  WARNINGS:

    1. Experimental module! Currently supports only one single value image
       field.

    2. Image field name is hardcoded - change NREFID_IMAGE_CCK_FIELD constant
       if your image fieldname is different.

  Modules with similar functionality:

    - Nodereference Image Helper
      http://drupal.org/project/noderef_image_helper

    - Node Reference Variables
      http://drupal.org/project/nodereference_variables

  Author: Vojtech Kusy <wojtha@gmail.com>

_______________________________________________________________________________

   INSTALLATION HOW-TO
_______________________________________________________________________________

  1. Install the module.
  2. Setup the "image" CCK content type with filefield or imagefield.
  3. Create a nodereference field which is able to reference this image type if
     you didn't have one yet.
  4. Change NREFID_IMAGE_CCK_FIELD constant if your image fieldname is
     different.
  5. Set a nodereference formatter on the Display Fields page.