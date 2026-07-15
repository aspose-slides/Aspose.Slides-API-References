---
title: Flavor
second_title: Aspose.Slides for Android via Java API 參考文件
description: 程式中使用的所有 markdown 規格。
type: docs
url: /zh-hant/com.aspose.slides/flavor/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

程式中使用的所有 markdown 規格。

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

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [Github](#Github) | Github 風格. |
| [Gruber](#Gruber) | Gruber 風格. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown 風格. |
| [CommonMark](#CommonMark) | Common mark 風格. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra 風格. |
| [Pandoc](#Pandoc) | Pandoc 風格. |
| [Kramdown](#Kramdown) | Kramdown 風格. |
| [Markua](#Markua) | Markua 風格. |
| [Maruku](#Maruku) | Maruku 風格. |
| [Markdown2](#Markdown2) | Markdown2 風格. |
| [Remarkable](#Remarkable) | Remarkable 風格 |
| [Showdown](#Showdown) | Showdown 風格. |
| [Ghost](#Ghost) | Ghost 風格. |
| [GitLab](#GitLab) | Gitlab 風格. |
| [Haroopad](#Haroopad) | Haroopad 風格. |
| [IaWriter](#IaWriter) | IAWriter 風格. |
| [Redcarpet](#Redcarpet) | Redcarpet 風格. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown 風格. |
| [Taiga](#Taiga) | Taiga 風格. |
| [Trello](#Trello) | Trello 風格. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter 風格. |
| [XWiki](#XWiki) | XWiki 風格. |
| [StackOverflow](#StackOverflow) | Stack overflow 風格. |
| [Default](#Default) | Default markdown 風格. |
### Github {#Github}
```
public static final int Github
```


Github 風格.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber 風格.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown 風格.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark 風格.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra 風格.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc 風格.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown 風格.

### Markua {#Markua}
```
public static final int Markua
```


Markua 風格.

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku 風格.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 風格.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable 風格

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown 風格.

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost 風格.

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab 風格.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad 風格.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter 風格.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet 風格.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown 風格.

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga 風格.

### Trello {#Trello}
```
public static final int Trello
```


Trello 風格.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter 風格.

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki 風格.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow 風格.

### Default {#Default}
```
public static final int Default
```


Default markdown 風格.