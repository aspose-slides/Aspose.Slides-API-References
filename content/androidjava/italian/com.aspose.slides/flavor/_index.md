---
title: Flavor
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Tutte le specifiche markdown utilizzate nel programma.
type: docs
url: /it/com.aspose.slides/flavor/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Tutte le specifiche markdown utilizzate nel programma.

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

## Campi

| Campo | Descrizione |
| --- | --- |
| [Github](#Github) | Stile Github. |
| [Gruber](#Gruber) | Stile Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Stile Multi markdown. |
| [CommonMark](#CommonMark) | Stile Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Stile Markdown extra. |
| [Pandoc](#Pandoc) | Stile Pandoc. |
| [Kramdown](#Kramdown) | Stile Kramdown. |
| [Markua](#Markua) | Stile Markua. |
| [Maruku](#Maruku) | Stile Maruku. |
| [Markdown2](#Markdown2) | Stile Markdown2. |
| [Remarkable](#Remarkable) | Stile Remarkable |
| [Showdown](#Showdown) | Stile Showdown. |
| [Ghost](#Ghost) | Stile Ghost. |
| [GitLab](#GitLab) | Stile Gitlab. |
| [Haroopad](#Haroopad) | Stile Haroopad. |
| [IaWriter](#IaWriter) | Stile IAWriter. |
| [Redcarpet](#Redcarpet) | Stile Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Stile Scholarly markdown. |
| [Taiga](#Taiga) | Stile Taiga. |
| [Trello](#Trello) | Stile Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Stile S9E text formatter. |
| [XWiki](#XWiki) | Stile XWiki. |
| [StackOverflow](#StackOverflow) | Stile Stack overflow. |
| [Default](#Default) | Stile markdown predefinito. |
### Github {#Github}
```
public static final int Github
```

Stile Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Stile Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Stile Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Stile Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Stile Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Stile Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Stile Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Stile Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Stile Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Stile Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Stile Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

Stile Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Stile Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Stile Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Stile Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Stile IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Stile Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Stile Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Stile Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Stile Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Stile S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Stile XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stile Stack overflow.

### Default {#Default}
```
public static final int Default
```

Stile markdown predefinito.