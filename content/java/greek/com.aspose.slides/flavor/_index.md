---
title: Flavor
second_title: Aspose.Slides για την Αναφορά API της Java
description: Όλες οι προδιαγραφές markdown που χρησιμοποιούνται στο πρόγραμμα.
type: docs
url: /el/com.aspose.slides/flavor/
---
**Κληρονόμηση:**
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

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Github](#Github) | Github έκδοση. |
| [Gruber](#Gruber) | Gruber έκδοση. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown έκδοση. |
| [CommonMark](#CommonMark) | Common mark έκδοση. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra έκδοση. |
| [Pandoc](#Pandoc) | Pandoc έκδοση. |
| [Kramdown](#Kramdown) | Kramdown έκδοση. |
| [Markua](#Markua) | Markua έκδοση. |
| [Maruku](#Maruku) | Maruku έκδοση. |
| [Markdown2](#Markdown2) | Markdown2 έκδοση. |
| [Remarkable](#Remarkable) | Remarkable έκδοση |
| [Showdown](#Showdown) | Showdown έκδοση. |
| [Ghost](#Ghost) | Ghost έκδοση. |
| [GitLab](#GitLab) | Gitlab έκδοση. |
| [Haroopad](#Haroopad) | Haroopad έκδοση. |
| [IaWriter](#IaWriter) | IAWriter έκδοση. |
| [Redcarpet](#Redcarpet) | Redcarpet έκδοση. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown έκδοση. |
| [Taiga](#Taiga) | Taiga έκδοση. |
| [Trello](#Trello) | Trello έκδοση. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter έκδοση. |
| [XWiki](#XWiki) | XWiki έκδοση. |
| [StackOverflow](#StackOverflow) | Stack overflow έκδοση. |
| [Default](#Default) | Default markdown έκδοση. |
### Github {#Github}
```
public static final int Github
```


Github έκδοση.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber έκδοση.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown έκδοση.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark έκδοση.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra έκδοση.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc έκδοση.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown έκδοση.

### Markua {#Markua}
```
public static final int Markua
```


Markua έκδοση.

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku έκδοση.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 έκδοση.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable έκδοση

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown έκδοση.

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost έκδοση.

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab έκδοση.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad έκδοση.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter έκδοση.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet έκδοση.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown έκδοση.

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga έκδοση.

### Trello {#Trello}
```
public static final int Trello
```


Trello έκδοση.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter έκδοση.

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki έκδοση.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow έκδοση.

### Default {#Default}
```
public static final int Default
```


Default markdown έκδοση.