---
title: Flavor
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: تمام مشخصات مارک‌داون مورد استفاده در برنامه.
type: docs
url: /fa/com.aspose.slides/flavor/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

تمام مشخصات مارک‌داون مورد استفاده در برنامه.

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
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Github](#Github) | طعم Github. |
| [Gruber](#Gruber) | طعم Gruber. |
| [MultiMarkdown](#MultiMarkdown) | طعم Multi markdown. |
| [CommonMark](#CommonMark) | طعم Common mark. |
| [MarkdownExtra](#MarkdownExtra) | طعم Markdown extra. |
| [Pandoc](#Pandoc) | طعم Pandoc. |
| [Kramdown](#Kramdown) | طعم Kramdown. |
| [Markua](#Markua) | طعم Markua. |
| [Maruku](#Maruku) | طعم Maruku. |
| [Markdown2](#Markdown2) | طعم Markdown2. |
| [Remarkable](#Remarkable) | طعم Remarkable |
| [Showdown](#Showdown) | طعم Showdown. |
| [Ghost](#Ghost) | طعم Ghost. |
| [GitLab](#GitLab) | طعم Gitlab. |
| [Haroopad](#Haroopad) | طعم Haroopad. |
| [IaWriter](#IaWriter) | طعم IAWriter. |
| [Redcarpet](#Redcarpet) | طعم Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | طعم Scholarly markdown. |
| [Taiga](#Taiga) | طعم Taiga. |
| [Trello](#Trello) | طعم Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | طعم S9E text formatter. |
| [XWiki](#XWiki) | طعم XWiki. |
| [StackOverflow](#StackOverflow) | طعم Stack overflow. |
| [Default](#Default) | طعم پیش‌فرض markdown. |
### Github {#Github}
```
public static final int Github
```

طعم Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

طعم Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

طعم Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

طعم Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

طعم Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

طعم Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

طعم Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

طعم Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

طعم Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

طعم Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

طعم Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

طعم Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

طعم Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

طعم Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

طعم Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

طعم IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

طعم Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

طعم Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

طعم Taiga.

### Trello {#Trello}
```
public static final int Trello
```

طعم Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

طعم S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

طعم XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

طعم Stack overflow.

### Default {#Default}
```
public static final int Default
```

طعم پیش‌فرض markdown.