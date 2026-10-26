---
title: Flavor
second_title: Aspose.Slides para Android via Referência de API Java
description: Todas as especificações de markdown usadas no programa.
type: docs
url: /pt/com.aspose.slides/flavor/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Todas as especificações de markdown usadas no programa.

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
## Campos

| Campo | Descrição |
| --- | --- |
| [Github](#Github) | Variante Github. |
| [Gruber](#Gruber) | Variante Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Variante Multi markdown. |
| [CommonMark](#CommonMark) | Variante Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Variante Markdown extra. |
| [Pandoc](#Pandoc) | Variante Pandoc. |
| [Kramdown](#Kramdown) | Variante Kramdown. |
| [Markua](#Markua) | Variante Markua. |
| [Maruku](#Maruku) | Variante Maruku. |
| [Markdown2](#Markdown2) | Variante Markdown2. |
| [Remarkable](#Remarkable) | Variante Remarkable |
| [Showdown](#Showdown) | Variante Showdown. |
| [Ghost](#Ghost) | Variante Ghost. |
| [GitLab](#GitLab) | Variante Gitlab. |
| [Haroopad](#Haroopad) | Variante Haroopad. |
| [IaWriter](#IaWriter) | Variante IAWriter. |
| [Redcarpet](#Redcarpet) | Variante Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Variante Scholarly markdown. |
| [Taiga](#Taiga) | Variante Taiga. |
| [Trello](#Trello) | Variante Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Variante S9E text formatter. |
| [XWiki](#XWiki) | Variante XWiki. |
| [StackOverflow](#StackOverflow) | Variante Stack overflow. |
| [Default](#Default) | Variante Default markdown. |
### Github {#Github}
```
public static final int Github
```


Variante Github.

### Gruber {#Gruber}
```
public static final int Gruber
```


Variante Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Variante Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Variante Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Variante Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Variante Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Variante Kramdown.

### Markua {#Markua}
```
public static final int Markua
```


Variante Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```


Variante Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Variante Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Variante Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```


Variante Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```


Variante Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```


Variante Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Variante Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


Variante IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Variante Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Variante Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```


Variante Taiga.

### Trello {#Trello}
```
public static final int Trello
```


Variante Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


Variante S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```


Variante XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Variante Stack overflow.

### Default {#Default}
```
public static final int Default
```


Variante Default markdown.