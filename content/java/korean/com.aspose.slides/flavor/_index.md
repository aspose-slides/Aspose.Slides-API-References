---
title: Flavor
second_title: Aspose.Slides for Java API 레퍼런스
description: 프로그램에서 사용되는 모든 마크다운 사양입니다.
type: docs
url: /ko/com.aspose.slides/flavor/
---
**Inheritance:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class Flavor extends System.Enum
```

프로그램에서 사용되는 모든 마크다운 사양입니다.

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

## 필드

| 필드 | 설명 |
| --- | --- |
| [Github](#Github) | Github 플레이버. |
| [Gruber](#Gruber) | Gruber 플레이버. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown 플레이버. |
| [CommonMark](#CommonMark) | Common mark 플레이버. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra 플레이버. |
| [Pandoc](#Pandoc) | Pandoc 플레이버. |
| [Kramdown](#Kramdown) | Kramdown 플레이버. |
| [Markua](#Markua) | Markua 플레이버. |
| [Maruku](#Maruku) | Maruku 플레이버. |
| [Markdown2](#Markdown2) | Markdown2 플레이버. |
| [Remarkable](#Remarkable) | Remarkable 플레이버 |
| [Showdown](#Showdown) | Showdown 플레이버. |
| [Ghost](#Ghost) | Ghost 플레이버. |
| [GitLab](#GitLab) | Gitlab 플레이버. |
| [Haroopad](#Haroopad) | Haroopad 플레이버. |
| [IaWriter](#IaWriter) | IAWriter 플레이버. |
| [Redcarpet](#Redcarpet) | Redcarpet 플레이버. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown 플레이버. |
| [Taiga](#Taiga) | Taiga 플레이버. |
| [Trello](#Trello) | Trello 플레이버. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter 플레이버. |
| [XWiki](#XWiki) | XWiki 플레이버. |
| [StackOverflow](#StackOverflow) | Stack overflow 플레이버. |
| [Default](#Default) | Default markdown 플레이버. |

### Github {#Github}
```
public static final int Github
```

Github 플레이버.

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber 플레이버.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown 플레이버.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark 플레이버.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra 플레이버.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc 플레이버.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown 플레이버.

### Markua {#Markua}
```
public static final int Markua
```

Markua 플레이버.

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku 플레이버.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 플레이버.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable 플레이버

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown 플레이버.

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost 플레이버.

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab 플레이버.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad 플레이버.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter 플레이버.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet 플레이버.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown 플레이버.

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga 플레이버.

### Trello {#Trello}
```
public static final int Trello
```

Trello 플레이버.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter 플레이버.

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki 플레이버.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow 플레이버.

### Default {#Default}
```
public static final int Default
```

Default markdown 플레이버.