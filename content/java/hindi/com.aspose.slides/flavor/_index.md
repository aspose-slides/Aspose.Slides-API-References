---
title: Flavor
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रोग्राम में उपयोग की गई सभी मार्कडाउन विनिर्देश।
type: docs
url: /hi/com.aspose.slides/flavor/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

प्रोग्राम में उपयोग की गई सभी मार्कडाउन विनिर्देश।

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
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Github](#Github) | Github फ़्लेवर। |
| [Gruber](#Gruber) | Gruber फ़्लेवर। |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown फ़्लेवर। |
| [CommonMark](#CommonMark) | Common mark फ़्लेवर। |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra फ़्लेवर। |
| [Pandoc](#Pandoc) | Pandoc फ़्लेवर। |
| [Kramdown](#Kramdown) | Kramdown फ़्लेवर। |
| [Markua](#Markua) | Markua फ़्लेवर। |
| [Maruku](#Maruku) | Maruku फ़्लेवर। |
| [Markdown2](#Markdown2) | Markdown2 फ़्लेवर। |
| [Remarkable](#Remarkable) | Remarkable फ़्लेवर |
| [Showdown](#Showdown) | Showdown फ़्लेवर। |
| [Ghost](#Ghost) | Ghost फ़्लेवर। |
| [GitLab](#GitLab) | Gitlab फ़्लेवर। |
| [Haroopad](#Haroopad) | Haroopad फ़्लेवर। |
| [IaWriter](#IaWriter) | IAWriter फ़्लेवर। |
| [Redcarpet](#Redcarpet) | Redcarpet फ़्लेवर। |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown फ़्लेवर। |
| [Taiga](#Taiga) | Taiga फ़्लेवर। |
| [Trello](#Trello) | Trello फ़्लेवर। |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter फ़्लेवर। |
| [XWiki](#XWiki) | XWiki फ़्लेवर। |
| [StackOverflow](#StackOverflow) | Stack overflow फ़्लेवर। |
| [Default](#Default) | Default markdown फ़्लेवर। |
### Github {#Github}
```
public static final int Github
```

Github फ़्लेवर।

### Gruber {#Gruber}
```
public static final int Gruber
```

Gruber फ़्लेवर।

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```

Multi markdown फ़्लेवर।

### CommonMark {#CommonMark}
```
public static final int CommonMark
```

Common mark फ़्लेवर।

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```

Markdown extra फ़्लेवर।

### Pandoc {#Pandoc}
```
public static final int Pandoc
```

Pandoc फ़्लेवर।

### Kramdown {#Kramdown}
```
public static final int Kramdown
```

Kramdown फ़्लेवर।

### Markua {#Markua}
```
public static final int Markua
```

Markua फ़्लेवर।

### Maruku {#Maruku}
```
public static final int Maruku
```

Maruku फ़्लेवर।

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```

Markdown2 फ़्लेवर।

### Remarkable {#Remarkable}
```
public static final int Remarkable
```

Remarkable फ़्लेवर

### Showdown {#Showdown}
```
public static final int Showdown
```

Showdown फ़्लेवर।

### Ghost {#Ghost}
```
public static final int Ghost
```

Ghost फ़्लेवर।

### GitLab {#GitLab}
```
public static final int GitLab
```

Gitlab फ़्लेवर।

### Haroopad {#Haroopad}
```
public static final int Haroopad
```

Haroopad फ़्लेवर।

### IaWriter {#IaWriter}
```
public static final int IaWriter
```

IAWriter फ़्लेवर।

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```

Redcarpet फ़्लेवर।

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```

Scholarly markdown फ़्लेवर।

### Taiga {#Taiga}
```
public static final int Taiga
```

Taiga फ़्लेवर।

### Trello {#Trello}
```
public static final int Trello
```

Trello फ़्लेवर।

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```

S9E text formatter फ़्लेवर।

### XWiki {#XWiki}
```
public static final int XWiki
```

XWiki फ़्लेवर।

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```

Stack overflow फ़्लेवर।

### Default {#Default}
```
public static final int Default
```

Default markdown फ़्लेवर।