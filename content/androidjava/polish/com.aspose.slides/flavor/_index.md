---
title: Flavor
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Wszystkie specyfikacje markdown użyte w programie.
type: docs
url: /pl/com.aspose.slides/flavor/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Wszystkie specyfikacje markdown użyte w programie.

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
## Pola

| Pole | Opis |
| --- | --- |
| [Github](#Github) | Wariant Github. |
| [Gruber](#Gruber) | Wariant Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Wariant Multi markdown. |
| [CommonMark](#CommonMark) | Wariant Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Wariant Markdown extra. |
| [Pandoc](#Pandoc) | Wariant Pandoc. |
| [Kramdown](#Kramdown) | Wariant Kramdown. |
| [Markua](#Markua) | Wariant Markua. |
| [Maruku](#Maruku) | Wariant Maruku. |
| [Markdown2](#Markdown2) | Wariant Markdown2. |
| [Remarkable](#Remarkable) | Wariant Remarkable |
| [Showdown](#Showdown) | Wariant Showdown. |
| [Ghost](#Ghost) | Wariant Ghost. |
| [GitLab](#GitLab) | Wariant Gitlab. |
| [Haroopad](#Haroopad) | Wariant Haroopad. |
| [IaWriter](#IaWriter) | Wariant IAWriter. |
| [Redcarpet](#Redcarpet) | Wariant Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Wariant Scholarly markdown. |
| [Taiga](#Taiga) | Wariant Taiga. |
| [Trello](#Trello) | Wariant Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Wariant S9E text formatter. |
| [XWiki](#XWiki) | Wariant XWiki. |
| [StackOverflow](#StackOverflow) | Wariant Stack overflow. |
| [Default](#Default) | Wariant domyślny markdown. |
### Github {#Github}
```
public static final int Github
```

Wariant Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Wariant Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Wariant Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Wariant Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Wariant Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Wariant Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Wariant Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Wariant Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Wariant Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Wariant Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Wariant Remarkable.

### Showdown {#Showdown}
```
public static final int Showdown
```

Wariant Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Wariant Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Wariant Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Wariant Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Wariant IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Wariant Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Wariant Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Wariant Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Wariant Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Wariant S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Wariant XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Wariant Stack overflow.

### Default {#Default}
```
public static final int Default
```

Wariant domyślny markdown.