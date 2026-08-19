---
title: Flavor
second_title: Aspose.Slides för Java API-referens
description: Alla markdown-specifikationer som används i programmet.
type: docs
url: /sv/com.aspose.slides/flavor/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Alla markdown-specifikationer som används i programmet.

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

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Github](#Github) | Github-smak. |
| [Gruber](#Gruber) | Gruber-smak. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown-smak. |
| [CommonMark](#CommonMark) | Common mark-smak. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra-smak. |
| [Pandoc](#Pandoc) | Pandoc-smak. |
| [Kramdown](#Kramdown) | Kramdown-smak. |
| [Markua](#Markua) | Markua-smak. |
| [Maruku](#Maruku) | Maruku-smak. |
| [Markdown2](#Markdown2) | Markdown2-smak. |
| [Remarkable](#Remarkable) | Remarkable-smak |
| [Showdown](#Showdown) | Showdown-smak. |
| [Ghost](#Ghost) | Ghost-smak. |
| [GitLab](#GitLab) | Gitlab-smak. |
| [Haroopad](#Haroopad) | Haroopad-smak. |
| [IaWriter](#IaWriter) | IAWriter-smak. |
| [Redcarpet](#Redcarpet) | Redcarpet-smak. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown-smak. |
| [Taiga](#Taiga) | Taiga-smak. |
| [Trello](#Trello) | Trello-smak. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter-smak. |
| [XWiki](#XWiki) | XWiki-smak. |
| [StackOverflow](#StackOverflow) | Stack overflow-smak. |
| [Default](#Default) | Standard markdown-smak. |
### Github {#Github}
```
public static final int Github
```


Github-smak.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber-smak.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown-smak.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark-smak.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra-smak.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc-smak.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown-smak.

### Markua {#Markua}
```
public static final int Markua
```


Markua-smak.

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku-smak.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2-smak.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable-smak

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown-smak.

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost-smak.

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab-smak.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad-smak.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter-smak.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet-smak.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown-smak.

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga-smak.

### Trello {#Trello}
```
public static final int Trello
```


Trello-smak.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter-smak.

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki-smak.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow-smak.

### Default {#Default}
```
public static final int Default
```


Standard markdown-smak.