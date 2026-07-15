---
title: Flavor
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Tất cả các đặc tả markdown được sử dụng trong chương trình.
type: docs
url: /vi/com.aspose.slides/flavor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Tất cả các đặc tả markdown được sử dụng trong chương trình.

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

## Trường

| Trường | Mô tả |
| --- | --- |
| [Github](#Github) | Phiên bản Github. |
| [Gruber](#Gruber) | Phiên bản Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Phiên bản Multi markdown. |
| [CommonMark](#CommonMark) | Phiên bản Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Phiên bản Markdown extra. |
| [Pandoc](#Pandoc) | Phiên bản Pandoc. |
| [Kramdown](#Kramdown) | Phiên bản Kramdown. |
| [Markua](#Markua) | Phiên bản Markua. |
| [Maruku](#Maruku) | Phiên bản Maruku. |
| [Markdown2](#Markdown2) | Phiên bản Markdown2. |
| [Remarkable](#Remarkable) | Phiên bản Remarkable |
| [Showdown](#Showdown) | Phiên bản Showdown. |
| [Ghost](#Ghost) | Phiên bản Ghost. |
| [GitLab](#GitLab) | Phiên bản Gitlab. |
| [Haroopad](#Haroopad) | Phiên bản Haroopad. |
| [IaWriter](#IaWriter) | Phiên bản IAWriter. |
| [Redcarpet](#Redcarpet) | Phiên bản Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Phiên bản Scholarly markdown. |
| [Taiga](#Taiga) | Phiên bản Taiga. |
| [Trello](#Trello) | Phiên bản Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Phiên bản S9E text formatter. |
| [XWiki](#XWiki) | Phiên bản XWiki. |
| [StackOverflow](#StackOverflow) | Phiên bản Stack overflow. |
| [Default](#Default) | Phiên bản Default markdown. |
### Github {#Github}
```
public static final int Github
```

Phiên bản Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Phiên bản Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Phiên bản Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Phiên bản Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Phiên bản Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Phiên bản Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Phiên bản Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Phiên bản Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Phiên bản Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Phiên bản Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Phiên bản Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

Phiên bản Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Phiên bản Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Phiên bản Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Phiên bản Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Phiên bản IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Phiên bản Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Phiên bản Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Phiên bản Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Phiên bản Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Phiên bản S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Phiên bản XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Phiên bản Stack overflow.

### Default {#Default}
```
public static final int Default
```

Phiên bản Default markdown.