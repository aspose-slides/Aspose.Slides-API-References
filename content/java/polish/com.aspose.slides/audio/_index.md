---
title: Audio
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje osadzony plik audio.
type: docs
url: /pl/com.aspose.slides/audio/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Reprezentuje osadzony plik audio.
## Metody

| Metoda | Opis |
| --- | --- |
| [getContentType()](#getContentType--) | Zwraca typ MIME dźwięku, zakodowany w (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Zwraca typ MIME dźwięku, zakodowany w (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Zwraca kopię danych audio. |
| [getStream()](#getStream--) | Zwraca Stream stream do odczytu. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Zwraca typ MIME dźwięku, zakodowany w (\#getBinaryData.getBinaryData). Tylko do odczytu String.

**Zwraca:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Zwraca typ MIME dźwięku, zakodowany w (\#getBinaryData.getBinaryData). Tylko do odczytu String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ użycie metody \#getStream.getStream, aby zapobiec niepotrzebnemu ładowaniu danych audio do pamięci lub nawet wyjątkowi OutOfMemoryException. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Zwraca Stream stream do odczytu. Użyj 'using' lub zamknij strumień po użyciu.

**Zwraca:**
java.io.InputStream - Strumień do odczytu.