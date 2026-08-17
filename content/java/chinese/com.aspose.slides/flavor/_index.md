---
title: Flavor
second_title: Aspose.Slides Java API 参考
description: 程序中使用的所有 markdown 规范。
type: docs
url: /zh/com.aspose.slides/flavor/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

该程序使用的所有 markdown 规范。

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

## 字段

| Field | Description |
| --- | --- |
| [Github](#Github) | Github 风格。 |
| [Gruber](#Gruber) | Gruber 风格。 |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown 风格。 |
| [CommonMark](#CommonMark) | Common mark 风格。 |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra 风格。 |
| [Pandoc](#Pandoc) | Pandoc 风格。 |
| [Kramdown](#Kramdown) | Kramdown 风格。 |
| [Markua](#Markua) | Markua 风格。 |
| [Maruku](#Maruku) | Maruku 风格。 |
| [Markdown2](#Markdown2) | Markdown2 风格。 |
| [Remarkable](#Remarkable) | Remarkable 风格 |
| [Showdown](#Showdown) | Showdown 风格。 |
| [Ghost](#Ghost) | Ghost 风格。 |
| [GitLab](#GitLab) | Gitlab 风格。 |
| [Haroopad](#Haroopad) | Haroopad 风格。 |
| [IaWriter](#IaWriter) | IAWriter 风格。 |
| [Redcarpet](#Redcarpet) | Redcarpet 风格。 |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown 风格。 |
| [Taiga](#Taiga) | Taiga 风格。 |
| [Trello](#Trello) | Trello 风格。 |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter 风格。 |
| [XWiki](#XWiki) | XWiki 风格。 |
| [StackOverflow](#StackOverflow) | Stack overflow 风格。 |
| [Default](#Default) | Default markdown 风格。 |
### Github {#Github}
```
public static final int Github
```


Github 风格。

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber 风格。

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown 风格。

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark 风格。

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra 风格。

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc 风格。

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown 风格。

### Markua {#Markua}
```
public static final int Markua
```


Markua 风格。

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku 风格。

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 风格。

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable 风格

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown 风格。

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost 风格。

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab 风格。

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad 风格。

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter 风格。

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet 风格。

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown 风格。

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga 风格。

### Trello {#Trello}
```
public static final int Trello
```


Trello 风格。

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter 风格。

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki 风格。

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow 风格。

### Default {#Default}
```
public static final int Default
```


Default markdown 风格。