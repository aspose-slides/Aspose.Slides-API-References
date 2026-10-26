---
title: Flavor
second_title: Référence de l'API Aspose.Slides pour Java
description: Toutes les spécifications markdown utilisées dans le programme.
type: docs
url: /fr/com.aspose.slides/flavor/
---
**Héritage :**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class Flavor extends System.Enum
```

Toutes les spécifications markdown utilisées dans le programme.

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

## Champs

| Champ | Description |
| --- | --- |
| [Github](#Github) | Saveur Github. |
| [Gruber](#Gruber) | Saveur Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Saveur Multi markdown. |
| [CommonMark](#CommonMark) | Saveur Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Saveur Markdown extra. |
| [Pandoc](#Pandoc) | Saveur Pandoc. |
| [Kramdown](#Kramdown) | Saveur Kramdown. |
| [Markua](#Markua) | Saveur Markua. |
| [Maruku](#Maruku) | Saveur Maruku. |
| [Markdown2](#Markdown2) | Saveur Markdown2. |
| [Remarkable](#Remarkable) | Saveur Remarkable |
| [Showdown](#Showdown) | Saveur Showdown. |
| [Ghost](#Ghost) | Saveur Ghost. |
| [GitLab](#GitLab) | Saveur Gitlab. |
| [Haroopad](#Haroopad) | Saveur Haroopad. |
| [IaWriter](#IaWriter) | Saveur IAWriter. |
| [Redcarpet](#Redcarpet) | Saveur Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Saveur Scholarly markdown. |
| [Taiga](#Taiga) | Saveur Taiga. |
| [Trello](#Trello) | Saveur Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Saveur S9E text formatter. |
| [XWiki](#XWiki) | Saveur XWiki. |
| [StackOverflow](#StackOverflow) | Saveur Stack overflow. |
| [Default](#Default) | Saveur markdown par défaut. |
### Github {#Github}
```
public static final int Github
```

Saveur Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

Saveur Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Saveur Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Saveur Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Saveur Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Saveur Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Saveur Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

Saveur Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

Saveur Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Saveur Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Saveur Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

Saveur Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

Saveur Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

Saveur Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Saveur Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

Saveur IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Saveur Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Saveur Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

Saveur Taiga.

### Trello {#Trello}
```
public static final int Trello
```

Saveur Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

Saveur S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

Saveur XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Saveur Stack overflow.

### Default {#Default}
```
public static final int Default
```

Saveur markdown par défaut.