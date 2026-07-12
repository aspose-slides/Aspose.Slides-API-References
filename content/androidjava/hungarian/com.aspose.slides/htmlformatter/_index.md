---
title: HtmlFormatter
second_title: Aspose.Slides for Android a Java API hivatkozással
description: HTML fájlsablont reprezentál.
type: docs
url: /hu/com.aspose.slides/htmlformatter/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML fájlsablont reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | HTML formázót hoz létre és ad vissza egy egyszerű dokumentumnézethez, amely egymás alatti diák sorozatából áll. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | HTML formázót hoz létre és ad vissza egy egyszerű diavetítés HTML-hez, amely egymás után jeleníti meg a diákat. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | HTML formázót hoz létre és ad vissza egy egyéni, visszahívás-alapú HTML-generáláshoz. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

HTML formázót hoz létre és ad vissza egy egyszerű dokumentumnézethez, amely egymás alatti diák sorozatából áll.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| css | java.lang.String | Megadja a CSS-t ehhez a fájlhoz. |
| showSlideTitle | boolean | Hozzáadja a dia címét, ha van az diaképet fölött. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

HTML formázót hoz létre és ad vissza egy egyszerű diavetítés HTML-hez, amely egymás után jeleníti meg a diákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| css | java.lang.String | Megadja a használt CSS fájl URL-jét. |
| showSlideTitle | boolean | Hozzáadja a dia címét, ha van az diaképet fölött. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

HTML formázót hoz létre és ad vissza egy egyéni, visszahívás-alapú HTML-generáláshoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Visszahívási interfész, amely szabályozza a HTML fájl generálását. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.