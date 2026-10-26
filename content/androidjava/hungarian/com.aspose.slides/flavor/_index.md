---
title: Flavor
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Az összes markdown specifikáció a programban használva.
type: docs
url: /hu/com.aspose.slides/flavor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Az összes markdown specifikáció a programban használva.

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

## Mezők

| Mező | Leírás |
| --- | --- |
| [Github](#Github) | Github változat. |
| [Gruber](#Gruber) | Gruber változat. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown változat. |
| [CommonMark](#CommonMark) | Common mark változat. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra változat. |
| [Pandoc](#Pandoc) | Pandoc változat. |
| [Kramdown](#Kramdown) | Kramdown változat. |
| [Markua](#Markua) | Markua változat. |
| [Maruku](#Maruku) | Maruku változat. |
| [Markdown2](#Markdown2) | Markdown2 változat. |
| [Remarkable](#Remarkable) | Remarkable változat |
| [Showdown](#Showdown) | Showdown változat. |
| [Ghost](#Ghost) | Ghost változat. |
| [GitLab](#GitLab) | Gitlab változat. |
| [Haroopad](#Haroopad) | Haroopad változat. |
| [IaWriter](#IaWriter) | IAWriter változat. |
| [Redcarpet](#Redcarpet) | Redcarpet változat. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown változat. |
| [Taiga](#Taiga) | Taiga változat. |
| [Trello](#Trello) | Trello változat. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter változat. |
| [XWiki](#XWiki) | XWiki változat. |
| [StackOverflow](#StackOverflow) | Stack overflow változat. |
| [Default](#Default) | Default markdown változat. |
### Github {#Github}
```
public static final int Github
```

Github változat.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber változat.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown változat.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark változat.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra változat.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc változat.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown változat.

### Markua {#Markua}
```
public static final int Markua
```

Markua változat.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku változat.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 változat.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable változat

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown változat.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost változat.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab változat.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad változat.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter változat.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet változat.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown változat.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga változat.

### Trello {#Trello}
```
public static final int Trello
```

Trello változat.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter változat.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki változat.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow változat.

### Default {#Default}
```
public static final int Default
```

Default markdown változat.