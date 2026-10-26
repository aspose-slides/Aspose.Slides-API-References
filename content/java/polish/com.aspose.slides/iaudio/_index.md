---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje osadzony plik audio.
type: docs
url: /pl/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Reprezentuje osadzony plik audio.
## Metody

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Zwraca typ MIME audio, zakodowany w (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Zwraca kopię danych audio. |
| [getStream()](#getStream--) | Zwraca strumień Stream do odczytu. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Zwraca typ MIME audio, zakodowany w (\#getBinaryData.getBinaryData). Tylko do odczytu String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ użycie metody \#getStream.getStream, aby zapobiec niepotrzebnemu ładowaniu danych audio do pamięci lub nawet wyjątku OutOfMemoryException. Tylko do odczytu byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Zwraca strumień Stream do odczytu. Użyj 'using' lub zamknij strumień po użyciu.

**Returns:**
java.io.InputStream - Stream for reading.