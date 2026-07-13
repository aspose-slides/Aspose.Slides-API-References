---
title: Video
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Reprezentuje obraz osadzony w prezentacji.
type: docs
url: /pl/com.aspose.slides/video/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Reprezentuje obraz osadzony w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getContentType()](#getContentType--) | Zwraca typ MIME wideo, zakodowany w (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Zwraca kopię danych audio. |
| [getStream()](#getStream--) | Zwraca Stream stream do odczytu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Zwraca typ MIME wideo, zakodowany w (\#getBinaryData.getBinaryData). Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ użycie metody \#getStream.getStream, aby zapobiec niepotrzebnemu ładowaniu danych wideo do pamięci lub nawet OutOfMemoryException. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Zwraca Stream stream do odczytu. Użyj 'using' lub zamknij strumień po użyciu.

**Zwraca:**
java.io.InputStream - Stream do odczytu.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject