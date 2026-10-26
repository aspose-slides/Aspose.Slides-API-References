---
title: MarkdownExportType
second_title: Aspose.Slides for Java API リファレンス
description: レンダリングドキュメントの種類。
type: docs
url: /ja/com.aspose.slides/markdownexporttype/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

レンダリングドキュメントの種類。

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
## フィールド

| Field | 説明 |
| --- | --- |
| [Sequential](#Sequential) | すべての項目を個別にレンダリングします。 |
| [TextOnly](#TextOnly) | テキストのみをレンダリングします。 |
| [Visual](#Visual) | すべての項目を、グループ化された項目はまとめてレンダリングします。 |
### Sequential {#Sequential}
```
public static final int Sequential
```


すべての項目を個別に、1つずつレンダリングします。

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


テキストのみをレンダリングします。

### Visual {#Visual}
```
public static final int Visual
```


すべての項目を、グループ化された項目はまとめてレンダリングします。