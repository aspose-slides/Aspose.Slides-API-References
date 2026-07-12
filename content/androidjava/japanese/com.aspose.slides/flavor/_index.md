---
title: Flavor
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プログラムで使用されているすべての Markdown 仕様。
type: docs
url: /ja/com.aspose.slides/flavor/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

プログラムで使用されているすべての Markdown 仕様。

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

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Github](#Github) | Github フレーバー。 |
| [Gruber](#Gruber) | Gruber フレーバー。 |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown フレーバー。 |
| [CommonMark](#CommonMark) | Common mark フレーバー。 |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra フレーバー。 |
| [Pandoc](#Pandoc) | Pandoc フレーバー。 |
| [Kramdown](#Kramdown) | Kramdown フレーバー。 |
| [Markua](#Markua) | Markua フレーバー。 |
| [Maruku](#Maruku) | Maruku フレーバー。 |
| [Markdown2](#Markdown2) | Markdown2 フレーバー。 |
| [Remarkable](#Remarkable) | Remarkable フレーバー |
| [Showdown](#Showdown) | Showdown フレーバー。 |
| [Ghost](#Ghost) | Ghost フレーバー。 |
| [GitLab](#GitLab) | Gitlab フレーバー。 |
| [Haroopad](#Haroopad) | Haroopad フレーバー。 |
| [IaWriter](#IaWriter) | IAWriter フレーバー。 |
| [Redcarpet](#Redcarpet) | Redcarpet フレーバー。 |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown フレーバー。 |
| [Taiga](#Taiga) | Taiga フレーバー。 |
| [Trello](#Trello) | Trello フレーバー。 |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter フレーバー。 |
| [XWiki](#XWiki) | XWiki フレーバー。 |
| [StackOverflow](#StackOverflow) | Stack overflow フレーバー。 |
| [Default](#Default) | Default markdown フレーバー。 |
### Github {#Github}
```
public static final int Github
```

Github フレーバー。

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber フレーバー。

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown フレーバー。

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark フレーバー。

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra フレーバー。

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc フレーバー。

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown フレーバー。

### Markua {#Markua}
```
public static final int Markua
```

Markua フレーバー。

### Maruku {#Maruku}
```
public static final int Maruka
```

Maruku フレーバー。

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 フレーバー。

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable フレーバー

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown フレーバー。

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost フレーバー。

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab フレーバー。

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad フレーバー。

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter フレーバー。

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet フレーバー。

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown フレーバー。

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga フレーバー。

### Trello {#Trello}
```
public static final int Trello
```

Trello フレーバー。

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter フレーバー。

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki フレーバー。

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow フレーバー。

### Default {#Default}
```
public static final int Default
```

Default markdown フレーバー。