---
title: Flavor
second_title: Aspose.Slides for Android عبر مرجع API Java
description: جميع مواصفات markdown المستخدمة في البرنامج.
type: docs
url: /ar/com.aspose.slides/flavor/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

جميع مواصفات markdown المستخدمة في البرنامج.

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

## الحقول

| الحقل | الوصف |
| --- | --- |
| [Github](#Github) | نمط Github. |
| [Gruber](#Gruber) | نمط Gruber. |
| [MultiMarkdown](#MultiMarkdown) | نمط Multi markdown. |
| [CommonMark](#CommonMark) | نمط Common mark. |
| [MarkdownExtra](#MarkdownExtra) | نمط Markdown extra. |
| [Pandoc](#Pandoc) | نمط Pandoc. |
| [Kramdown](#Kramdown) | نمط Kramdown. |
| [Markua](#Markua) | نمط Markua. |
| [Maruku](#Maruku) | نمط Maruku. |
| [Markdown2](#Markdown2) | نمط Markdown2. |
| [Remarkable](#Remarkable) | نمط Remarkable |
| [Showdown](#Showdown) | نمط Showdown. |
| [Ghost](#Ghost) | نمط Ghost. |
| [GitLab](#GitLab) | نمط Gitlab. |
| [Haroopad](#Haroopad) | نمط Haroopad. |
| [IaWriter](#IaWriter) | نمط IAWriter. |
| [Redcarpet](#Redcarpet) | نمط Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | نمط Scholarly markdown. |
| [Taiga](#Taiga) | نمط Taiga. |
| [Trello](#Trello) | نمط Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | نمط S9E text formatter. |
| [XWiki](#XWiki) | نمط XWiki. |
| [StackOverflow](#StackOverflow) | نمط Stack overflow. |
| [Default](#Default) | نمط الافتراضي markdown. |
### Github {#Github}
```
public static final int Github
```

نمط Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

نمط Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

نمط Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

نمط Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

نمط Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

نمط Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

نمط Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

نمط Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

نمط Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

نمط Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

نمط Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

نمط Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

نمط Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

نمط Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

نمط Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

نمط IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

نمط Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

نمط Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

نمط Taiga.

### Trello {#Trello}
```
public static final int Trello
```

نمط Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

نمط S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

نمط XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

نمط Stack overflow.

### Default {#Default}
```
public static final int Default
```

نمط الافتراضي markdown.