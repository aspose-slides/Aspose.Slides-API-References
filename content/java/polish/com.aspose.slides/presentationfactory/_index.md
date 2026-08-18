---
title: PresentationFactory
second_title: Aspose.Slides dla Java - odniesienie API
description: Umożliwia tworzenie prezentacji za pośrednictwem interfejsu COM
type: docs
url: /pl/com.aspose.slides/presentationfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Umożliwia tworzenie prezentacji za pośrednictwem interfejsu COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInstance()](#getInstance--) | Statyczna instancja fabryki prezentacji. |
| [createPresentation()](#createPresentation--) | Tworzy nową prezentację. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Tworzy nową prezentację z dodatkowymi opcjami ładowania |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Tworzy nowy obiekt PresentationInfo z pliku i wiąże prezentację z nim. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Tworzy nowy obiekt PresentationInfo ze strumienia i wiąże prezentację z nim. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Odczytuje istniejącą prezentację z tablicy |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami ładowania |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Odczytuje istniejącą prezentację ze strumienia |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Odczytuje istniejącą prezentację z pliku |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Pobiera surowy tekst ze slajdów |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Pobiera surowy tekst ze slajdów |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Pobiera surowy tekst ze slajdów |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Statyczna instancja fabryki prezentacji. Tylko do odczytu [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Zwraca:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Tworzy nową prezentację.

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nową prezentację
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Tworzy nową prezentację z dodatkowymi opcjami ładowania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje ładowania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nową prezentację
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Tworzy nowy obiekt PresentationInfo z pliku i wiąże prezentację z nim.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik prezentacji. |

**Zwraca:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informacje o prezentacji połączone z prezentacją.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Tworzy nowy obiekt PresentationInfo ze strumienia i wiąże prezentację z nim. Pobiera informacje o prezentacji w określonym strumieniu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień prezentacji. |

**Zwraca:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informacje o prezentacji połączone z prezentacją.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Odczytuje istniejącą prezentację z tablicy

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Tablica do odczytu |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Odczytuje istniejącą prezentację z tablicy z dodatkowymi opcjami ładowania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Tablica do odczytu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje ładowania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Odczytuje istniejącą prezentację ze strumienia

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy do odczytu |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy do odczytu |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje ładowania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPPresentation readPresentation(String file)
```

Odczytuje istniejącą prezentację z pliku

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Nazwa pliku |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Odczytuje istniejącą prezentację ze strumienia z dodatkowymi opcjami ładowania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Nazwa pliku |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje ładowania |

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation) - Odczytaną prezentację
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
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
public final IPresentationText getPresentationText(InputStream stream, int mode)
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
public final IPPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Pobiera surowy tekst ze slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy |
| mode | int | Tryb ekstrakcji |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opcje ładowania |

**Zwraca:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instancja PresentationText zawierająca tablicę SlideText reprezentującą surowy tekst slajdów