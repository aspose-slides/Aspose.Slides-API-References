---
title: PdfOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/pdfoptions/
---

## PdfOptions class

 Provides options that control how a presentation is saved in Pdf format.
 

 The following example shows how to convert PowerPoint to PDF with custom options.
 
```php
  $pres = new Presentation("PowerPoint.pptx");
  try {
    // Instantiates the PdfOptions class
    $pdfOptions = new PdfOptions();
    // Sets the Jpeg quality
    $pdfOptions->setJpegQuality(90);
    // Sets the behavior for metafiles
    $pdfOptions->setSaveMetafilesAsPng(true);
    // Sets the text compression level
    $pdfOptions->setTextCompression(PdfTextCompression.Flate);
    // Defines the PDF standard
    $pdfOptions->setCompliance(PdfCompliance.Pdf15);
    // Saves the presentation as a PDF
    $pres->save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, $pdfOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [getAccessPermissions](getaccesspermissions)() | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |
| [getAdditionalCommonFontFamilies](getadditionalcommonfontfamilies)() | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [getApplyImageTransparent](getapplyimagetransparent)() | Applies the specified transparent color to an image if true. |
| [getBestImagesCompressionRatio](getbestimagescompressionratio)() | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |
| [getCompliance](getcompliance)() | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf15. |
| [getDrawSlidesFrame](getdrawslidesframe)() | True to draw black frame around each slide. Read/write boolean. Default is false. |
| [getEmbedFullFonts](getembedfullfonts)() | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |
| [getEmbedTrueTypeFontsForASCII](getembedtruetypefontsforascii)() | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |
| [getImageTransparentColor](getimagetransparentcolor)() | Gets or sets the image transparent color. Value: The color of the image transparent. |
| [getJpegQuality](getjpegquality)() | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [getNotesCommentsLayouting](getnotescommentslayouting)() | Provides options that control how notes and comments is placed in exported document. |
| [getPassword](getpassword)() | Setting user password to protect the PDF document. Read/write String. |
| [getSaveMetafilesAsPng](getsavemetafilesaspng)() | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |
| [getShowHiddenSlides](getshowhiddenslides)() | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [getSufficientResolution](getsufficientresolution)() | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |
| [getTextCompression](gettextcompression)() | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |
| [setAccessPermissions](setaccesspermissions)(int) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |
| [setAdditionalCommonFontFamilies](setadditionalcommonfontfamilies)(java.lang.String[]) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [setApplyImageTransparent](setapplyimagetransparent)(boolean) | Applies the specified transparent color to an image if true. |
| [setBestImagesCompressionRatio](setbestimagescompressionratio)(boolean) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |
| [setCompliance](setcompliance)(int) | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf15. |
| [setDrawSlidesFrame](setdrawslidesframe)(boolean) | True to draw black frame around each slide. Read/write boolean. Default is false. |
| [setEmbedFullFonts](setembedfullfonts)(boolean) | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |
| [setEmbedTrueTypeFontsForASCII](setembedtruetypefontsforascii)(boolean) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |
| [setImageTransparentColor](setimagetransparentcolor)(Color) | Gets or sets the image transparent color. Value: The color of the image transparent. |
| [setJpegQuality](setjpegquality)(OrderedDictionary) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [setJpegQuality](setjpegquality)(Hashtable) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [setJpegQuality](setjpegquality)(LinkedList) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [setPassword](setpassword)(String) | Setting user password to protect the PDF document. Read/write String. |
| [setSaveMetafilesAsPng](setsavemetafilesaspng)(boolean) | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |
| [setShowHiddenSlides](setshowhiddenslides)(boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [setSufficientResolution](setsufficientresolution)(float) | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |
| [setTextCompression](settextcompression)(int) | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |
