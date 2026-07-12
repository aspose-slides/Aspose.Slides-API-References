---
title: Flavor
second_title: Aspose.Slides für Android über Java API-Referenz
description: Alle im Programm verwendeten Markdown-Spezifikationen.
type: docs
url: /de/com.aspose.slides/flavor/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Alle in diesem Programm verwendeten Markdown-Spezifikationen.

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Github](#Github) | Github-Variante. |
| [Gruber](#Gruber) | Gruber-Variante. |
| [MultiMarkdown](#MultiMarkdown) | Multi-Markdown-Variante. |
| [CommonMark](#CommonMark) | Common-Mark-Variante. |
| [MarkdownExtra](#MarkdownExtra) | Markdown-Extra-Variante. |
| [Pandoc](#Pandoc) | Pandoc-Variante. |
| [Kramdown](#Kramdown) | Kramdown-Variante. |
| [Markua](#Markua) | Markua-Variante. |
| [Maruku](#Maruku) | Maruku-Variante. |
| [Markdown2](#Markdown2) | Markdown2-Variante. |
| [Remarkable](#Remarkable) | Remarkable-Variante |
| [Showdown](#Showdown) | Showdown-Variante. |
| [Ghost](#Ghost) | Ghost-Variante. |
| [GitLab](#GitLab) | Gitlab-Variante. |
| [Haroopad](#Haroopad) | Haroopad-Variante. |
| [IaWriter](#IaWriter) | IAWriter-Variante. |
| [Redcarpet](#Redcarpet) | Redcarpet-Variante. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly-Markdown-Variante. |
| [Taiga](#Taiga) | Taiga-Variante. |
| [Trello](#Trello) | Trello-Variante. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E-Text-Formatter-Variante. |
| [XWiki](#XWiki) | XWiki-Variante. |
| [StackOverflow](#StackOverflow) | Stack-Overflow-Variante. |
| [Default](#Default) | Standard-Markdown-Variante. |
### Github {#Github}
```
public static final int Github
```

Github-Variante.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber-Variante.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi-Markdown-Variante.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common-Mark-Variante.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown-Extra-Variante.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc-Variante.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown-Variante.

### Markua {#Markua}
```
public static final int Markua
```

Markua-Variante.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku-Variante.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2-Variante.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable-Variante

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown-Variante.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost-Variante.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab-Variante.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad-Variante.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter-Variante.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet-Variante.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly-Markdown-Variante.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga-Variante.

### Trello {#Trello}
```
public static final int Trello
```

Trello-Variante.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E-Text-Formatter-Variante.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki-Variante.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack-Overflow-Variante.

### Default {#Default}
```
public static final int Default
```

Standard-Markdown-Variante.