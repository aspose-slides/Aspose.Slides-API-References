---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /pl/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Metody

| Metoda | Opis |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Funkcja zwrotna, która zostanie wywołana dla każdego [Slide](../../com.aspose.slides/slide), powinna zwrócić ścieżkę wyjściową. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Funkcja zwrotna, która zostanie wywołana dla każdego [Slide](../../com.aspose.slides/slide), powinna zwrócić ścieżkę wyjściową.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Obecny iterowany slajd |
| index | int | Indeks bieżącego slajdu |

**Zwraca:**
java.lang.String