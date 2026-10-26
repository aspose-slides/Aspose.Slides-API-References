---
title: Flavor
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Semua spesifikasi markdown yang digunakan dalam program.
type: docs
url: /id/com.aspose.slides/flavor/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Semua spesifikasi markdown yang digunakan dalam program.

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

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Github](#Github) | Varian Github. |
| [Gruber](#Gruber) | Varian Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Varian Multi markdown. |
| [CommonMark](#CommonMark) | Varian Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Varian Markdown extra. |
| [Pandoc](#Pandoc) | Varian Pandoc. |
| [Kramdown](#Kramdown) | Varian Kramdown. |
| [Markua](#Markua) | Varian Markua. |
| [Maruku](#Maruku) | Varian Maruku. |
| [Markdown2](#Markdown2) | Varian Markdown2. |
| [Remarkable](#Remarkable) | Varian Remarkable |
| [Showdown](#Showdown) | Varian Showdown. |
| [Ghost](#Ghost) | Varian Ghost. |
| [GitLab](#GitLab) | Varian Gitlab. |
| [Haroopad](#Haroopad) | Varian Haroopad. |
| [IaWriter](#IaWriter) | Varian IAWriter. |
| [Redcarpet](#Redcarpet) | Varian Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Varian Scholarly markdown. |
| [Taiga](#Taiga) | Varian Taiga. |
| [Trello](#Trello) | Varian Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Varian S9E text formatter. |
| [XWiki](#XWiki) | Varian XWiki. |
| [StackOverflow](#StackOverflow) | Varian Stack overflow. |
| [Default](#Default) | Varian Default markdown. |
### Github {#Github}
```
public static final int Github
```

Varian Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Varian Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Varian Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Varian Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Varian Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Varian Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Varian Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Varian Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Varian Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Varian Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Varian Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

Varian Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Varian Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Varian Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Varian Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Varian IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Varian Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Varian Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Varian Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Varian Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Varian S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Varian XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Varian Stack overflow.

### Default {#Default}
```
public static final int Default
```

Varian Default markdown.