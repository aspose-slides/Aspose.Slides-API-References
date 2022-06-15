---
title: PdfOptions
type: docs
weight: 0
url: /php-java/pdfoptions/
---

# PdfOptions class

 Provides options that control how a presentation is saved in Pdf format.
 

## Constructors

| name | description |
| --- | --- |
| [PdfOptions](/slides/php-java/pdfoptions/pdfoptions/)() | Default constructor. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAccessPermissions](/slides/php-java/pdfoptions/getaccesspermissions/)() | int | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |
| [getAdditionalCommonFontFamilies](/slides/php-java/pdfoptions/getadditionalcommonfontfamilies/)() | String | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [getApplyImageTransparent](/slides/php-java/pdfoptions/getapplyimagetransparent/)() | boolean | Applies the specified transparent color to an image if true. |
| [getBestImagesCompressionRatio](/slides/php-java/pdfoptions/getbestimagescompressionratio/)() | boolean | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |
| [getCompliance](/slides/php-java/pdfoptions/getcompliance/)() | int | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf15. |
| [getDrawSlidesFrame](/slides/php-java/pdfoptions/getdrawslidesframe/)() | boolean | True to draw black frame around each slide. Read/write boolean. Default is false. |
| [getEmbedFullFonts](/slides/php-java/pdfoptions/getembedfullfonts/)() | boolean | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |
| [getEmbedTrueTypeFontsForASCII](/slides/php-java/pdfoptions/getembedtruetypefontsforascii/)() | boolean | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |
| [getImageTransparentColor](/slides/php-java/pdfoptions/getimagetransparentcolor/)() | Color | Gets or sets the image transparent color. Value: The color of the image transparent. |
| [getJpegQuality](/slides/php-java/pdfoptions/getjpegquality/)() | byte | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [getNotesCommentsLayouting](/slides/php-java/pdfoptions/getnotescommentslayouting/)() | INotesCommentsLayoutingOptions | Provides options that control how notes and comments is placed in exported document. |
| [getPassword](/slides/php-java/pdfoptions/getpassword/)() | String | Setting user password to protect the PDF document. Read/write String. |
| [getSaveMetafilesAsPng](/slides/php-java/pdfoptions/getsavemetafilesaspng/)() | boolean | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |
| [getShowHiddenSlides](/slides/php-java/pdfoptions/getshowhiddenslides/)() | boolean | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [getSufficientResolution](/slides/php-java/pdfoptions/getsufficientresolution/)() | float | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |
| [getTextCompression](/slides/php-java/pdfoptions/gettextcompression/)() | int | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |
| [setAccessPermissions](/slides/php-java/pdfoptions/setaccesspermissions/)(int) | void | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |
| [setAdditionalCommonFontFamilies](/slides/php-java/pdfoptions/setadditionalcommonfontfamilies/)(java.lang.String[]) | void | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [setApplyImageTransparent](/slides/php-java/pdfoptions/setapplyimagetransparent/)(boolean) | void | Applies the specified transparent color to an image if true. |
| [setBestImagesCompressionRatio](/slides/php-java/pdfoptions/setbestimagescompressionratio/)(boolean) | void | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |
| [setCompliance](/slides/php-java/pdfoptions/setcompliance/)(int) | void | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf15. |
| [setDrawSlidesFrame](/slides/php-java/pdfoptions/setdrawslidesframe/)(boolean) | void | True to draw black frame around each slide. Read/write boolean. Default is false. |
| [setEmbedFullFonts](/slides/php-java/pdfoptions/setembedfullfonts/)(boolean) | void | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |
| [setEmbedTrueTypeFontsForASCII](/slides/php-java/pdfoptions/setembedtruetypefontsforascii/)(boolean) | void | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |
| [setImageTransparentColor](/slides/php-java/pdfoptions/setimagetransparentcolor/)(Color) | void | Gets or sets the image transparent color. Value: The color of the image transparent. |
| [setJpegQuality](/slides/php-java/pdfoptions/setjpegquality/)(byte) | void | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |
| [setPassword](/slides/php-java/pdfoptions/setpassword/)(String) | void | Setting user password to protect the PDF document. Read/write String. |
| [setSaveMetafilesAsPng](/slides/php-java/pdfoptions/setsavemetafilesaspng/)(boolean) | void | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |
| [setShowHiddenSlides](/slides/php-java/pdfoptions/setshowhiddenslides/)(boolean) | void | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [setSufficientResolution](/slides/php-java/pdfoptions/setsufficientresolution/)(float) | void | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |
| [setTextCompression](/slides/php-java/pdfoptions/settextcompression/)(int) | void | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |
