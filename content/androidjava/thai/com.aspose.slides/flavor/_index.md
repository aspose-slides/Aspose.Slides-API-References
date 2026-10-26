---
title: Flavor
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: สเปค Markdown ทั้งหมดที่ใช้ในโปรแกรม.
type: docs
url: /th/com.aspose.slides/flavor/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

สเปค Markdown ทั้งหมดที่ใช้ในโปรแกรม.

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

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Github](#Github) | รูปแบบ Github. |
| [Gruber](#Gruber) | รูปแบบ Gruber. |
| [MultiMarkdown](#MultiMarkdown) | รูปแบบ Multi markdown. |
| [CommonMark](#CommonMark) | รูปแบบ Common mark. |
| [MarkdownExtra](#MarkdownExtra) | รูปแบบ Markdown extra. |
| [Pandoc](#Pandoc) | รูปแบบ Pandoc. |
| [Kramdown](#Kramdown) | รูปแบบ Kramdown. |
| [Markua](#Markua) | รูปแบบ Markua. |
| [Maruku](#Maruku) | รูปแบบ Maruku. |
| [Markdown2](#Markdown2) | รูปแบบ Markdown2. |
| [Remarkable](#Remarkable) | รูปแบบ Remarkable |
| [Showdown](#Showdown) | รูปแบบ Showdown. |
| [Ghost](#Ghost) | รูปแบบ Ghost. |
| [GitLab](#GitLab) | รูปแบบ Gitlab. |
| [Haroopad](#Haroopad) | รูปแบบ Haroopad. |
| [IaWriter](#IaWriter) | รูปแบบ IAWriter. |
| [Redcarpet](#Redcarpet) | รูปแบบ Redcarpet. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | รูปแบบ Scholarly markdown. |
| [Taiga](#Taiga) | รูปแบบ Taiga. |
| [Trello](#Trello) | รูปแบบ Trello. |
| [S9ETextFormatter](#S9ETextFormatter) | รูปแบบ S9E text formatter. |
| [XWiki](#XWiki) | รูปแบบ XWiki. |
| [StackOverflow](#StackOverflow) | รูปแบบ Stack overflow. |
| [Default](#Default) | รูปแบบ Default markdown. |
### Github {#Github}
```
public static final int Github
```

รูปแบบ Github.

### Gruber {#Gruber}
```
public static final int Gruber
```

รูปแบบ Gruber.

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

รูปแบบ Multi markdown.

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

รูปแบบ Common mark.

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

รูปแบบ Markdown extra.

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

รูปแบบ Pandoc.

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

รูปแบบ Kramdown.

### Markua {#Markua}
```
public static final int Markua
```

รูปแบบ Markua.

### Maruku {#Maruku}
```
public static final int Maruku
```

รูปแบบ Maruku.

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

รูปแบบ Markdown2.

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

รูปแบบ Remarkable

### Showdown {#Showdown}
```
public static final int Showdown
```

รูปแบบ Showdown.

### Ghost {#Ghost}
```
public static final int Ghost
```

รูปแบบ Ghost.

### GitLab {#GitLab}
```
public static final int GitLab
```

รูปแบบ Gitlab.

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

รูปแบบ Haroopad.

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

รูปแบบ IAWriter.

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

รูปแบบ Redcarpet.

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

รูปแบบ Scholarly markdown.

### Taiga {#Taiga}
```
public static final int Taiga
```

รูปแบบ Taiga.

### Trello {#Trello}
```
public static final int Trello
```

รูปแบบ Trello.

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

รูปแบบ S9E text formatter.

### XWiki {#XWiki}
```
public static final int XWiki
```

รูปแบบ XWiki.

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

รูปแบบ Stack overflow.

### Default {#Default}
```
public static final int Default
```

รูปแบบ Default markdown.