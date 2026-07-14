---
title: NewLineType
second_title: Aspose.Slides for Android via Java API संदर्भ
description: उत्पन्न दस्तावेज़ में उपयोग की जाने वाली नई पंक्ति का प्रकार।
type: docs
url: /hi/com.aspose.slides/newlinetype/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

उत्पन्न दस्तावेज़ में उपयोग की जाने वाली नई पंक्ति का प्रकार।

--------------------

> ```
> Example
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) | Mac (OS 9) नई पंक्ति - \\\\r |
### विंडोज {#Windows}
```
public static final int Windows
```


### यूनिक्स {#Unix}
```
public static final int Unix
```


### मैक {#Mac}
```
public static final int Mac
```


Mac (OS 9) नई पंक्ति - \\\\r