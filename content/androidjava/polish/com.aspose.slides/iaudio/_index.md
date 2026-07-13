---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
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

**Zwraca:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Zwraca kopię danych audio. W przypadku dużej ilości danych rozważ użycie metody \#getStream.getStream, aby zapobiec niepotrzebnemu ładowaniu danych audio do pamięci lub nawet wyjątku OutOfMemoryException. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Zwraca strumień Stream do odczytu. Użyj 'using' lub zamknij strumień po użyciu.

**Zwraca:**
java.io.InputStream - Strumień do odczytu.