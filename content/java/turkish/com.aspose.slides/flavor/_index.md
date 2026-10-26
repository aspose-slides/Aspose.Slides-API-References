---
title: Flavor
second_title: Aspose.Slides için Java API Referansı
description: Programda kullanılan tüm markdown spesifikasyonları.
type: docs
url: /tr/com.aspose.slides/flavor/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Programda kullanılan tüm markdown spesifikasyonları.

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

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Github](#Github) | Github biçimi. |
| [Gruber](#Gruber) | Gruber biçimi. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown biçimi. |
| [CommonMark](#CommonMark) | Common mark biçimi. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra biçimi. |
| [Pandoc](#Pandoc) | Pandoc biçimi. |
| [Kramdown](#Kramdown) | Kramdown biçimi. |
| [Markua](#Markua) | Markua biçimi. |
| [Maruku](#Maruku) | Maruku biçimi. |
| [Markdown2](#Markdown2) | Markdown2 biçimi. |
| [Remarkable](#Remarkable) | Remarkable biçimi |
| [Showdown](#Showdown) | Showdown biçimi. |
| [Ghost](#Ghost) | Ghost biçimi. |
| [GitLab](#GitLab) | Gitlab biçimi. |
| [Haroopad](#Haroopad) | Haroopad biçimi. |
| [IaWriter](#IaWriter) | IAWriter biçimi. |
| [Redcarpet](#Redcarpet) | Redcarpet biçimi. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown biçimi. |
| [Taiga](#Taiga) | Taiga biçimi. |
| [Trello](#Trello) | Trello biçimi. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter biçimi. |
| [XWiki](#XWiki) | XWiki biçimi. |
| [StackOverflow](#StackOverflow) | Stack overflow biçimi. |
| [Default](#Default) | Default markdown biçimi. |

### Github {#Github}
```
public static final int Github
```

Github biçimi.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber biçimi.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown biçimi.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark biçimi.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra biçimi.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc biçimi.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown biçimi.

### Markua {#Markua}
```
public static final int Markua
```

Markua biçimi.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku biçimi.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 biçimi.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable biçimi

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown biçimi.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost biçimi.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab biçimi.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad biçimi.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter biçimi.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet biçimi.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown biçimi.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga biçimi.

### Trello {#Trello}
```
public static final int Trello
```

Trello biçimi.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter biçimi.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki biçimi.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow biçimi.

### Default {#Default}
```
public static final int Default
```

Default markdown biçimi.