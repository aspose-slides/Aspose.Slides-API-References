---
title: Flavor
second_title: Aspose.Slides for Java API Reference
description: All markdown specifications used in program.
type: docs
url: /com.aspose.slides/flavor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

All markdown specifications used in program.

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
## Fields

| Field | Description |
| --- | --- |
| [Github](#Github) | Github flavor. |
| [Gruber](#Gruber) | Gruber flavor. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown flavor. |
| [CommonMark](#CommonMark) | Common mark flavor. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra flavor. |
| [Pandoc](#Pandoc) | Pandoc flavor. |
| [Kramdown](#Kramdown) | Kramdown flavor. |
| [Markua](#Markua) | Markua flavor. |
| [Maruku](#Maruku) | Maruku flavor. |
| [Markdown2](#Markdown2) | Markdown2 flavor. |
| [Remarkable](#Remarkable) | Remarkable flavor |
| [Showdown](#Showdown) | Showdown flavor. |
| [Ghost](#Ghost) | Ghost flavor. |
| [GitLab](#GitLab) | Gitlab flavor. |
| [Haroopad](#Haroopad) | Haroopad flavor. |
| [IaWriter](#IaWriter) | IAWriter flavor. |
| [Redcarpet](#Redcarpet) | Redcarpet flavor. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown flavor. |
| [Taiga](#Taiga) | Taiga flavor. |
| [Trello](#Trello) | Trello flavor. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter flavor. |
| [XWiki](#XWiki) | XWiki flavor. |
| [StackOverflow](#StackOverflow) | Stack overflow flavor. |
| [Default](#Default) | Default markdown flavor. |
### Github {#Github}
```
public static final int Github
```


Github flavor.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber flavor.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown flavor.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark flavor.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra flavor.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc flavor.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown flavor.

### Markua {#Markua}
```
public static final int Markua
```


Markua flavor.

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku flavor.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 flavor.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable flavor

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown flavor.

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost flavor.

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab flavor.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad flavor.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter flavor.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet flavor.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown flavor.

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga flavor.

### Trello {#Trello}
```
public static final int Trello
```


Trello flavor.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter flavor.

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki flavor.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow flavor.

### Default {#Default}
```
public static final int Default
```


Default markdown flavor.

