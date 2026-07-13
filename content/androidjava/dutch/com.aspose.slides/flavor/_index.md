---
title: Flavor
second_title: Aspose.Slides voor Android via Java API-referentie
description: Alle markdown-specificaties die in het programma worden gebruikt.
type: docs
url: /nl/com.aspose.slides/flavor/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Alle markdown-specificaties die in het programma worden gebruikt.

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
## Velden

| Field | Description |
| --- | --- |
| [Github](#Github) | Github variant. |
| [Gruber](#Gruber) | Gruber variant. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown variant. |
| [CommonMark](#CommonMark) | Common mark variant. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra variant. |
| [Pandoc](#Pandoc) | Pandoc variant. |
| [Kramdown](#Kramdown) | Kramdown variant. |
| [Markua](#Markua) | Markua variant. |
| [Maruku](#Maruku) | Maruku variant. |
| [Markdown2](#Markdown2) | Markdown2 variant. |
| [Remarkable](#Remarkable) | Remarkable variant |
| [Showdown](#Showdown) | Showdown variant. |
| [Ghost](#Ghost) | Ghost variant. |
| [GitLab](#GitLab) | Gitlab variant. |
| [Haroopad](#Haroopad) | Haroopad variant. |
| [IaWriter](#IaWriter) | IAWriter variant. |
| [Redcarpet](#Redcarpet) | Redcarpet variant. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown variant. |
| [Taiga](#Taiga) | Taiga variant. |
| [Trello](#Trello) | Trello variant. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter variant. |
| [XWiki](#XWiki) | XWiki variant. |
| [StackOverflow](#StackOverflow) | Stack overflow variant. |
| [Default](#Default) | Default markdown variant. |
### Github {#Github}
```
public static final int Github
```

Github variant.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber variant.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown variant.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark variant.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra variant.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc variant.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown variant.

### Markua {#Markua}
```
public static final int Markua
```

Markua variant.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku variant.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 variant.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable variant

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown variant.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost variant.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab variant.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad variant.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter variant.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet variant.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown variant.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga variant.

### Trello {#Trello}
```
public static final int Trello
```

Trello variant.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter variant.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki variant.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow variant.

### Default {#Default}
```
public static final int Default
```

Default markdown variant.