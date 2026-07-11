---
title: Flavor
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Όλες οι προδιαγραφές markdown που χρησιμοποιούνται στο πρόγραμμα.
type: docs
url: /el/com.aspose.slides/flavor/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Όλες οι προδιαγραφές markdown που χρησιμοποιούνται στο πρόγραμμα.

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
| [Github](#Github) | Έκδοση Github. |
| [Gruber](#Gruber) | Έκδοση Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Έκδοση Multi markdown. |
| [CommonMark](#CommonMark) | Έκδοση Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Έκδοση Markdown extra. |
| [Pandoc](#Pandoc) | Έκδοση Pandoc. |
| [Kramdown](#Kramdown) | Έκδοση Kramdown. |
| [Markua](#Markua) | Έκδοση Markua. |
| [Maruku](#Maruku) | Έκδοση Maruku. |
| [Markdown2](#Markdown2) | Έκδοση Markdown2. |
| [Remarkable](#Remarkable) | Έκδοση Remarkable |
| [Showdown](#Showdown) | Έκδοση Showdown. |
| [Ghost](#Ghost) | Έκδοση Ghost. |
| [GitLab](#GitLab) | Έκδοση Gitlab. |
| [Haroopad](#Haroopad) | Έκδοση Haroopad. |
| [IaWriter](#IaWriter) | Έκδοση IAWriter. |
| [Redcarpet](#Redcarpet) | Έκδοση Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Έκδοση Scholarly markdown. |
| [Taiga](#Taiga) | Έκδοση Taiga. |
| [Trello](#Trello) | Έκδοση Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Έκδοση S9E text formatter. |
| [XWiki](#XWiki) | Έκδοση XWiki. |
| [StackOverflow](#StackOverflow) | Έκδοση Stack overflow. |
| [Default](#Default) | Έκδοση Default markdown. |
### Github {#Github}
```
public static final int Github
```

Έκδοση Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Έκδοση Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Έκδοση Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Έκδοση Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Έκδοση Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Έκδοση Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Έκδοση Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Έκδοση Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Έκδοση Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Έκδοση Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Έκδοση Remarkable.

### Showdown {#Showdown}
```
public static final int Showdown
```

Έκδοση Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Έκδοση Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Έκδοση Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Έκδοση Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Έκδοση IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Έκδοση Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Έκδοση Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Έκδοση Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Έκδοση Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Έκδοση S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Έκδοση XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Έκδοση Stack overflow.

### Default {#Default}
```
public static final int Default
```

Έκδοση Default markdown.