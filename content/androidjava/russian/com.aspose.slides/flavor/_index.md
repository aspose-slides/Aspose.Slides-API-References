---
title: Flavor
second_title: Aspose.Slides для Android через справочник Java API
description: Все спецификации markdown, используемые в программе.
type: docs
url: /ru/com.aspose.slides/flavor/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

Все спецификации markdown, используемые в программе.

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

## Поля

| Поле | Описание |
| --- | --- |
| [Github](#Github) | Вариант Github. |
| [Gruber](#Gruber) | Вариант Gruber. |
| [MultiMarkdown](#MultiMarkdown) | Вариант Multi markdown. |
| [CommonMark](#CommonMark) | Вариант Common mark. |
| [MarkdownExtra](#MarkdownExtra) | Вариант Markdown extra. |
| [Pandoc](#Pandoc) | Вариант Pandoc. |
| [Kramdown](#Kramdown) | Вариант Kramdown. |
| [Markua](#Markua) | Вариант Markua. |
| [Maruku](#Maruku) | Вариант Maruku. |
| [Markdown2](#Markdown2) | Вариант Markdown2. |
| [Remarkable](#Remarkable) | Вариант Remarkable |
| [Showdown](#Showdown) | Вариант Showdown. |
| [Ghost](#Ghost) | Вариант Ghost. |
| [GitLab](#GitLab) | Вариант Gitlab. |
| [Haroopad](#Haroopad) | Вариант Haroopad. |
| [IaWriter](#IaWriter) | Вариант IAWriter. |
| [Redcarpet](#Redcarpet) | Вариант Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Вариант Scholarly markdown. |
| [Taiga](#Taiga) | Вариант Taiga. |
| [Trello](#Trello) | Вариант Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | Вариант S9E text formatter. |
| [XWiki](#XWiki) | Вариант XWiki. |
| [StackOverflow](#StackOverflow) | Вариант Stack overflow. |
| [Default](#Default) | Вариант Default markdown. |
### Github {#Github}
```
public static final int Github
```


Вариант Github.

### Gruber {#Gruber}
```
public static final int Gruber
```


Вариант Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Вариант Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Вариант Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Вариант Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Вариант Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Вариант Kramdown.

### Markua {#Markua}
```
public static final int Markua
```


Вариант Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```


Вариант Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Вариант Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Вариант Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```


Вариант Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```


Вариант Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```


Вариант Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Вариант Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


Вариант IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Вариант Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Вариант Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```


Вариант Taiga.

### Trello {#Trello}
```
public static final int Trello
```


Вариант Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


Вариант S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```


Вариант XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Вариант Stack overflow.

### Default {#Default}
```
public static final int Default
```


Вариант Default markdown.