---
title: Flavor
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Todas las especificaciones markdown usadas en el programa.
type: docs
url: /es/com.aspose.slides/flavor/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Todas las especificaciones markdown usadas en el programa.

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

| Campo | Descripción |
| --- | --- |
| [Github](#Github) | Sabor Github. |
| [Gruber](#Gruber) | Sabor Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Sabor Multi markdown. |
| [CommonMark](#CommonMark) | Sabor Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Sabor Markdown extra. |
| [Pandoc](#Pandoc) | Sabor Pandoc. |
| [Kramdown](#Kramdown) | Sabor Kramdown. |
| [Markua](#Markua) | Sabor Markua. |
| [Maruku](#Maruku) | Sabor Maruku. |
| [Markdown2](#Markdown2) | Sabor Markdown2. |
| [Remarkable](#Remarkable) | Sabor Remarkable |
| [Showdown](#Showdown) | Sabor Showdown. |
| [Ghost](#Ghost) | Sabor Ghost. |
| [GitLab](#GitLab) | Sabor Gitlab. |
| [Haroopad](#Haroopad) | Sabor Haroopad. |
| [IaWriter](#IaWriter) | Sabor IAWriter. |
| [Redcarpet](#Redcarpet) | Sabor Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Sabor Scholarly markdown. |
| [Taiga](#Taiga) | Sabor Taiga. |
| [Trello](#Trello) | Sabor Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Sabor S9E text formatter. |
| [XWiki](#XWiki) | Sabor XWiki. |
| [StackOverflow](#StackOverflow) | Sabor Stack overflow. |
| [Default](#Default) | Sabor Default markdown. |
### Github {#Github}
```
public static final int Github
```


Sabor Github.

### Gruber {#Gruber}
```
public static final int Gruber
```


Sabor Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Sabor Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Sabor Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Sabor Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Sabor Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Sabor Kramdown.

### Markua {#Markua}
```
public static final int Markua
```


Sabor Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```


Sabor Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Sabor Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Sabor Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```


Sabor Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```


Sabor Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```


Sabor Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Sabor Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


Sabor IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Sabor Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Sabor Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```


Sabor Taiga.

### Trello {#Trello}
```
public static final int Trello
```


Sabor Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


Sabor S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```


Sabor XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Sabor Stack overflow.

### Default {#Default}
```
public static final int Default
```


Sabor Default markdown.