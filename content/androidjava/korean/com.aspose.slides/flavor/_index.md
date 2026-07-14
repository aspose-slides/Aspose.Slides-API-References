---
title: Flavor
second_title: Java API 레퍼런스를 이용한 Android용 Aspose.Slides
description: 프로그램에서 사용되는 모든 마크다운 사양.
type: docs
url: /ko/com.aspose.slides/flavor/
---
**상속:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

프로그램에 사용되는 모든 마크다운 사양.

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [Github](#Github) | Github 변형. |
| [Gruber](#Gruber) | Gruber 변형. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown 변형. |
| [CommonMark](#CommonMark) | Common mark 변형. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra 변형. |
| [Pandoc](#Pandoc) | Pandoc 변형. |
| [Kramdown](#Kramdown) | Kramdown 변형. |
| [Markua](#Markua) | Markua 변형. |
| [Maruku](#Maruku) | Maruku 변형. |
| [Markdown2](#Markdown2) | Markdown2 변형. |
| [Remarkable](#Remarkable) | Remarkable 변형 |
| [Showdown](#Showdown) | Showdown 변형. |
| [Ghost](#Ghost) | Ghost 변형. |
| [GitLab](#GitLab) | Gitlab 변형. |
| [Haroopad](#Haroopad) | Haroopad 변형. |
| [IaWriter](#IaWriter) | IAWriter 변형. |
| [Redcarpet](#Redcarpet) | Redcarpet 변형. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown 변형. |
| [Taiga](#Taiga) | Taiga 변형. |
| [Trello](#Trello) | Trello 변형. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter 변형. |
| [XWiki](#XWiki) | XWiki 변형. |
| [StackOverflow](#StackOverflow) | Stack overflow 변형. |
| [Default](#Default) | Default markdown 변형. |
### Github {#Github}
```
public static final int Github
```

Github 변형.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber 변형.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown 변형.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark 변형.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra 변형.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc 변형.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown 변형.

### Markua {#Markua}
```
public static final int Markua
```

Markua 변형.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku 변형.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 변형.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable 변형

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown 변형.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost 변형.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab 변형.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad 변형.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter 변형.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet 변형.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown 변형.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga 변형.

### Trello {#Trello}
```
public static final int Trello
```

Trello 변형.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter 변형.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki 변형.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow 변형.

### Default {#Default}
```
public static final int Default
```

Default markdown 변형.