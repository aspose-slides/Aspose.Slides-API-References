---
title: Flavor
second_title: Aspose.Slides for Java API Reference
description: All markdown specifications used in program.
type: docs
weight: 199
url: /java/com.aspose.slides/flavor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Flavor extends System.Enum
```

All markdown specifications used in program.

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
## Fields

| Field | Description |
| --- | --- |
| [Github](#Github) | Github flavor. |
| [Gruber](#Gruber) | Gruber flavor. |
| [MultiMarkdown](#MultiMarkdown) | Multi markdown flavor. |
| [CommonMark](#CommonMark) | Common mark flavor. |
| [MarkdownExtra](#MarkdownExtra) | Markdown extra flavor. |
| [Pandoc](#Pandoc) | Pandoc flavor. |
| [Kramdown](#Kramdown) | Kramdown flavor. |
| [Markua](#Markua) | Markua flavor. |
| [Maruku](#Maruku) | Maruku flavor. |
| [Markdown2](#Markdown2) | Markdown2 flavor. |
| [Remarkable](#Remarkable) | Remarkable flavor Documentation: https://github.com/jonschlinkert/remarkable\#syntax-extensions |
| [Showdown](#Showdown) | Showdown flavor. |
| [Ghost](#Ghost) | Ghost flavor. |
| [GitLab](#GitLab) | Gitlab flavor. |
| [Haroopad](#Haroopad) | Haroopad flavor. |
| [IaWriter](#IaWriter) | IAWriter flavor. |
| [Redcarpet](#Redcarpet) | Redcarpet flavor. |
| [ScholarlyMarkdown](#ScholarlyMarkdown) | Scholarly markdown flavor. |
| [Taiga](#Taiga) | Taiga flavor. |
| [Trello](#Trello) | Trello flavor. |
| [S9ETextFormatter](#S9ETextFormatter) | S9E text formatter flavor. |
| [XWiki](#XWiki) | XWiki flavor. |
| [StackOverflow](#StackOverflow) | Stack overflow flavor. |
| [Default](#Default) | Default markdown flavor. |
### Github {#Github}
```
public static final int Github
```


Github flavor. Documentation: https://docs.github.com/en/github/writing-on-github.

### Gruber {#Gruber}
```
public static final int Gruber
```


Gruber flavor. Documentation: https://daringfireball.net/projects/markdown/syntax

### MultiMarkdown {#MultiMarkdown}
```
public static final int MultiMarkdown
```


Multi markdown flavor. Documentation: http://fletcher.github.io/MultiMarkdown-4/

### CommonMark {#CommonMark}
```
public static final int CommonMark
```


Common mark flavor. Documentation: https://spec.commonmark.org/

### MarkdownExtra {#MarkdownExtra}
```
public static final int MarkdownExtra
```


Markdown extra flavor. Documentation: https://github.com/vimtaai/extramark

### Pandoc {#Pandoc}
```
public static final int Pandoc
```


Pandoc flavor. Documentation: https://pandoc.org/MANUAL.html\#pandocs-markdown

### Kramdown {#Kramdown}
```
public static final int Kramdown
```


Kramdown flavor. Documentation: https://kramdown.gettalong.org/quickref.html

### Markua {#Markua}
```
public static final int Markua
```


Markua flavor. Documentation: http://markua.com/

### Maruku {#Maruku}
```
public static final int Maruku
```


Maruku flavor. Documentation: http://maruku.rubyforge.org/maruku.html

### Markdown2 {#Markdown2}
```
public static final int Markdown2
```


Markdown2 flavor. Documentation: https://markdown2.github.io/docs/home.html

### Remarkable {#Remarkable}
```
public static final int Remarkable
```


Remarkable flavor Documentation: https://github.com/jonschlinkert/remarkable\#syntax-extensions

### Showdown {#Showdown}
```
public static final int Showdown
```


Showdown flavor. Documentation: https://github.com/showdownjs/showdown/wiki

### Ghost {#Ghost}
```
public static final int Ghost
```


Ghost flavor. Documentation: https://github.com/TryGhost/Ghost\#features

### GitLab {#GitLab}
```
public static final int GitLab
```


Gitlab flavor. Documentation: https://docs.gitlab.com/ce/user/markdown.html

### Haroopad {#Haroopad}
```
public static final int Haroopad
```


Haroopad flavor. Documentation: http://pad.haroopress.com/page.html?f=haroopad-flavored-markdown

### IaWriter {#IaWriter}
```
public static final int IaWriter
```


IAWriter flavor. Documentation: https://ia.net/writer/support/general/markdown-guide

### Redcarpet {#Redcarpet}
```
public static final int Redcarpet
```


Redcarpet flavor. Documentation: https://github.com/vmg/redcarpet

### ScholarlyMarkdown {#ScholarlyMarkdown}
```
public static final int ScholarlyMarkdown
```


Scholarly markdown flavor. Documentation: http://scholarlymarkdown.com/Scholarly-Markdown-Guide.html

### Taiga {#Taiga}
```
public static final int Taiga
```


Taiga flavor. Documentation: https://resources.taiga.io/taiga-markdown-syntax/

### Trello {#Trello}
```
public static final int Trello
```


Trello flavor. Documentation: https://help.trello.com/article/821-using-markdown-in-trello

### S9ETextFormatter {#S9ETextFormatter}
```
public static final int S9ETextFormatter
```


S9E text formatter flavor. Documentation: https://s9etextformatter.readthedocs.io/Plugins/Litedown/Synopsis/

### XWiki {#XWiki}
```
public static final int XWiki
```


XWiki flavor. Documentation: https://www.xwiki.org/xwiki/bin/view/Documentation/UserGuide/Features/XWikiSyntax/

### StackOverflow {#StackOverflow}
```
public static final int StackOverflow
```


Stack overflow flavor. Documentation: https://stackoverflow.com/editing-help

### Default {#Default}
```
public static final int Default
```


Default markdown flavor.

