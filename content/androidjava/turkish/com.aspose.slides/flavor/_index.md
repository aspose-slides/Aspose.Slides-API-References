---
title: Flavor
second_title: Aspose.Slides for Android via Java API Referansı
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
| [Github](#Github) | Github türü. |
| [Gruber](#Gruber) | Gruber türü. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown türü. |
| [CommonMark](#CommonMark) | Common mark türü. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra türü. |
| [Pandoc](#Pandoc) | Pandoc türü. |
| [Kramdown](#Kramdown) | Kramdown türü. |
| [Markua](#Markua) | Markua türü. |
| [Maruku](#Maruku) | Maruku türü. |
| [Markdown2](#Markdown2) | Markdown2 türü. |
| [Remarkable](#Remarkable) | Remarkable türü |
| [Showdown](#Showdown) | Showdown türü. |
| [Ghost](#Ghost) | Ghost türü. |
| [GitLab](#GitLab) | Gitlab türü. |
| [Haroopad](#Haroopad) | Haroopad türü. |
| [IaWriter](#IaWriter) | IAWriter türü. |
| [Redcarpet](#Redcarpet) | Redcarpet türü. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown türü. |
| [Taiga](#Taiga) | Taiga türü. |
| [Trello](#Trello) | Trello türü. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter türü. |
| [XWiki](#XWiki) | XWiki türü. |
| [StackOverflow](#StackOverflow) | Stack overflow türü. |
| [Default](#Default) | Varsayılan markdown türü. |
### Github {#Github}
```
public static final int Github
```

Github türü.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber türü.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown türü.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark türü.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra türü.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc türü.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown türü.

### Markua {#Markua}
```
public static final int Markua
```

Markua türü.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku türü.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 türü.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable türü

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown türü.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost türü.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab türü.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad türü.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter türü.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet türü.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown türü.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga türü.

### Trello {#Trello}
```
public static final int Trello
```

Trello türü.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter türü.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki türü.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow türü.

### Default {#Default}
```
public static final int Default
```

Varsayılan markdown türü.