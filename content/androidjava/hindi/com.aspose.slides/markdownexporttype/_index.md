---
title: MarkdownExportType
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस द्वारा
description: दस्तावेज़ को रेंडर करने का प्रकार।
type: docs
url: /hi/com.aspose.slides/markdownexporttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

दस्तावेज़ को रेंडर करने का प्रकार।

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
| [Sequential](#Sequential) | सभी आइटम को अलग-अलग रेंडर करें। |
| [TextOnly](#TextOnly) | केवल पाठ को रेंडर करें। |
| [Visual](#Visual) | सभी आइटम को रेंडर करें, समूहित आइटम को साथ- साथ रेंडर किया जायेगा। |
### Sequential {#Sequential}
```
public static final int Sequential
```


सभी आइटम को अलग-अलग, एक-एक करके रेंडर करता है।

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


केवल पाठ को रेंडर करता है।

### Visual {#Visual}
```
public static final int Visual
```


सभी आइटम को रेंडर करता है, समूहित आइटम को साथ- साथ रेंडर किया जायेगा।