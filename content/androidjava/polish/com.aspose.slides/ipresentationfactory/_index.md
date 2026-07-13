---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create presentation via COM interface
type: docs
url: /pl/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Umożliwia tworzenie prezentacji za pośrednictwem interfejsu COM

## Metody

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Tworzy nową prezentację. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Tworzy nową prezentację z dodatkowymi opcjami wczytywania |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Pobiera informacje o prezentacji w określonym pliku. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Pobiera informacje o prezentacji w określonym strumieniu. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Odczytuje istniejącą prezentację z tablicy |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami wczytywania |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Odczytuje istniejącą prezentację ze strumienia |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami wczytywania |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Odczytuje istniejącą prezentację z pliku |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami wczytywania |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Pobiera surowy tekst ze slajdów |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Pobiera surowy tekst ze slajdów |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Pobiera surowy tekst ze slajdów |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Tworzy nową prezentację.

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nowa prezentacja

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


Tworzy nową prezentację z dodatkowymi opcjami wczytywania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje wczytywania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nowa prezentacja

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


Pobiera informacje o prezentacji w określonym pliku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik prezentacji. |

**Zwraca:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informacje o prezentacji

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Pobiera informacje o prezentacji w określonym strumieniu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień prezentacji. |

**Zwraca:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informacje o prezentacji.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Odczytuje istniejącą prezentację z tablicy

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Tablica do odczytu |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami wczytywania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Tablica do odczytu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje wczytywania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Odczytuje istniejącą prezentację ze strumienia

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy do odczytu |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami wczytywania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy do odczytu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje wczytywania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Odczytuje istniejącą prezentację z pliku

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Nazwa pliku |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Odczytuje istniejącą prezentację z pliku z dodatkowymi opcjami wczytywania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Nazwa pliku |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje wczytywania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytana prezentacja

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Pobiera surowy tekst ze slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik wejściowy |
| mode | int | Tryb ekstrakcji |

**Zwraca:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instancja PresentationText zawierająca tablicę SlideText reprezentującą surowy tekst slajdów

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Pobiera surowy tekst ze slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy |
| mode | int | Tryb ekstrakcji |

**Zwraca:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instancja PresentationText zawierająca tablicę SlideText reprezentującą surowy tekst slajdów

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Pobiera surowy tekst ze slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy |
| mode | int | Tryb ekstrakcji |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje wczytywania |

**Zwraca:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instancja PresentationText zawierająca tablicę SlideText reprezentującą surowy tekst slajdów