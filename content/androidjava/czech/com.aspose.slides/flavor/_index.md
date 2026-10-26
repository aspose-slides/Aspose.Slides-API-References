---
title: Flavor
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Všechny specifikace markdown použité v programu.
type: docs
url: /cs/com.aspose.slides/flavor/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Všechny specifikace markdown použité v programu.

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
## Pole

| Pole | Popis |
| --- | --- |
| [Github](#Github) | Github varianta. |
| [Gruber](#Gruber) | Gruber varianta. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown varianta. |
| [CommonMark](#CommonMark) | Common mark varianta. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra varianta. |
| [Pandoc](#Pandoc) | Pandoc varianta. |
| [Kramdown](#Kramdown) | Kramdown varianta. |
| [Markua](#Markua) | Markua varianta. |
| [Maruku](#Maruku) | Maruku varianta. |
| [Markdown2](#Markdown2) | Markdown2 varianta. |
| [Remarkable](#Remarkable) | Remarkable varianta |
| [Showdown](#Showdown) | Showdown varianta. |
| [Ghost](#Ghost) | Ghost varianta. |
| [GitLab](#GitLab) | Gitlab varianta. |
| [Haroopad](#Haroopad) | Haroopad varianta. |
| [IaWriter](#IaWriter) | IAWriter varianta. |
| [Redcarpet](#Redcarpet) | Redcarpet varianta. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown varianta. |
| [Taiga](#Taiga) | Taiga varianta. |
| [Trello](#Trello) | Trello varianta. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter varianta. |
| [XWiki](#XWiki) | XWiki varianta. |
| [StackOverflow](#StackOverflow) | Stack overflow varianta. |
| [Default](#Default) | Výchozí markdown varianta. |
### Github {#Github}
```
public static final int Github
```


Github varianta.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber varianta.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown varianta.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark varianta.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra varianta.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc varianta.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown varianta.

### Markua {#Markua}
```
public static final int Markua
```


Markua varianta.

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku varianta.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 varianta.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable varianta

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown varianta.

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost varianta.

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab varianta.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad varianta.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter varianta.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet varianta.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown varianta.

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga varianta.

### Trello {#Trello}
```
public static final int Trello
```


Trello varianta.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter varianta.

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki varianta.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow varianta.

### Default {#Default}
```
public static final int Default
```


Výchozí markdown varianta.