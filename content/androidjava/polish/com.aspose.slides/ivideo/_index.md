---
title: IVideo
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Reprezentuje wideo osadzone w prezentacji.
type: docs
url: /pl/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Reprezentuje wideo osadzone w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getContentType()](#getContentType--) | Zwraca typ MIME wideo, zakodowany w (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Zwraca kopię danych audio. |
| [getStream()](#getStream--) | Zwraca strumień Stream do odczytu. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Zwraca typ MIME wideo, zakodowany w (\#getBinaryData.getBinaryData). Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ użycie metody \#getStream.getStream, aby zapobiec niepotrzebnemu ładowaniu danych wideo do pamięci lub nawet wyjątku OutOfMemoryException. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Zwraca strumień Stream do odczytu. Użyj 'using' lub zamknij strumień po użyciu.

**Zwraca:**
java.io.InputStream - Strumień do odczytu.