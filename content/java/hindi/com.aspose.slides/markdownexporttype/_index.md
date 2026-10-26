---
title: MarkdownExportType
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: दस्तावेज़ रेंडरिंग का प्रकार।
type: docs
url: /hi/com.aspose.slides/markdownexporttype/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

दस्तावेज़ रेंडरिंग का प्रकार।

--------------------

> ```
> Example:
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
| [Sequential](#Sequential) | सभी आइटम अलग-अलग रेंडर करें। |
| [TextOnly](#TextOnly) | केवल टेक्स्ट रेंडर करें। |
| [Visual](#Visual) | सभी आइटम रेंडर करें, समूहित आइटम - साथ में रेंडर करें। |
### Sequential {#Sequential}
```
public static final int Sequential
```

सभी आइटम अलग-अलग रेंडर करें। एक-एक करके।

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

केवल टेक्स्ट रेंडर करें।

### Visual {#Visual}
```
public static final int Visual
```

सभी आइटम रेंडर करें, समूहित आइटम - साथ में रेंडर करें।