---
title: HtmlFormatter
second_title: Aspose.Slides Java API-referencia
description: HTML fájlsablont képvisel.
type: docs
url: /hu/com.aspose.slides/htmlformatter/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML fájlsablont képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Létrehozza és visszaadja a HTML formázót egy egyszerű dokumentumnézethez, amely egymás alatti diák sorozatából áll. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Létrehozza és visszaadja a HTML formázót egy egyszerű diavetítéshez, amely egymás után jeleníti meg a diákat. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Létrehozza és visszaadja a HTML formázót egy egyéni, visszahívás-alapú HTML generáláshoz. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Létrehozza és visszaadja a HTML formázót egy egyszerű dokumentumnézethez, amely egymás alatti diák sorozatából áll.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| css | java.lang.String | Megadja a CSS-t ehhez a fájlhoz. |
| showSlideTitle | boolean | A diacím hozzáadása, ha van a dia kép felett. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - a [HtmlFormatter](../../com.aspose.slides/htmlformatter) objektum.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Létrehozza és visszaadja a HTML formázót egy egyszerű diavetítéshez, amely egymás után jeleníti meg a diákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| css | java.lang.String | Megadja a használt CCS fájl URL-jét. |
| showSlideTitle | boolean | A diacím hozzáadása, ha van a dia kép felett. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - a [HtmlFormatter](../../com.aspose.slides/htmlformatter) objektum.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Létrehozza és visszaadja a HTML formázót egy egyéni, visszahívás-alapú HTML generáláshoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Visszahívási interfész, amely szabályozza a HTML fájl generálását. |

**Visszatérési érték:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - a [HtmlFormatter](../../com.aspose.slides/htmlformatter) objektum.