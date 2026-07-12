---
title: ITextSearchOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options that can be used to search for text in a Presentation Slide or TextFrame.
type: docs
url: /tr/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

Bir Presentation, Slide veya TextFrame içinde metin aramak için kullanılabilecek seçenekleri temsil eder.
## Methods

| Method | Description |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | Doğru ayarlandığında büyük/küçük harfe duyarlı arama kullanılır, yanlış ayarlandığında kullanılmaz. |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | Doğru ayarlandığında büyük/küçük harfe duyarlı arama kullanılır, yanlış ayarlandığında kullanılmaz. |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | Doğru ayarlandığında yalnızca tam kelimeler eşleştirilir, yanlış ise aksi. |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | Doğru ayarlandığında yalnızca tam kelimeler eşleştirilir, yanlış ise aksi. |
| [getIncludeNotes()](#getIncludeNotes--) | Doğru ayarlandığında slayt notlarında bulunan metin, metin arama, değiştirme veya vurgulama işlemleri sırasında dahil edilir. |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | Doğru ayarlandığında slayt notlarında bulunan metin, metin arama, değiştirme veya vurgulama işlemleri sırasında dahil edilir. |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```


Doğru ayarlandığında büyük/küçük harfe duyarlı arama kullanılır, yanlış ayarlandığında kullanılmaz. Okuma/yazma boolean.

**Döndürür:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


Doğru ayarlandığında büyük/küçük harfe duyarlı arama kullanılır, yanlış ayarlandığında kullanılmaz. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


Doğru ayarlandığında yalnızca tam kelimeler eşleştirilir, yanlış ise aksi. Okuma/yazma boolean.

**Döndürür:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


Doğru ayarlandığında yalnızca tam kelimeler eşleştirilir, yanlış ise aksi. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


Doğru ayarlandığında slayt notlarında bulunan metin, metin arama, değiştirme veya vurgulama işlemleri sırasında dahil edilir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


Doğru ayarlandığında slayt notlarında bulunan metin, metin arama, değiştirme veya vurgulama işlemleri sırasında dahil edilir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |