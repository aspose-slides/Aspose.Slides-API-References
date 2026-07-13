---
title: IImage
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
description: Reprezentuje obraz rastrowy lub wektorowy.
type: docs
url: /pl/com.aspose.slides/iimage/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Reprezentuje obraz rastrowy lub wektorowy.

--------------------

Ten interfejs zapewnia wspólną abstrakcję do obsługi zarówno obrazów rastrowych, jak i wektorowych. Implementacje mogą się różnić w zależności od podstawowego typu obrazu.
## Metody

| Metoda | Opis |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Zapisuje obraz do pliku. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Zapisuje obraz do pliku w określonym formacie. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Zapisuje obraz do strumienia w określonym formacie. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Zapisuje obraz do pliku w określonym formacie i jakości. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Zapisuje obraz do strumienia w określonym formacie i jakości. |
| [getSize()](#getSize--) | Pobiera rozmiar obrazu. |
| [getWidth()](#getWidth--) | Pobiera szerokość obrazu w pikselach. |
| [getHeight()](#getHeight--) | Pobiera wysokość obrazu w pikselach. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Zapisuje obraz do pliku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | java.lang.String | Ścieżka do pliku, w którym zostanie zapisany obraz. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Zapisuje obraz do pliku w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | java.lang.String | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | int | Format obrazu. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Zapisuje obraz do strumienia w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień, w którym zostanie zapisany obraz. |
| format | int | Format obrazu. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Zapisuje obraz do pliku w określonym formacie i jakości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | java.lang.String | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | int | Format obrazu. |
| quality | int | Jakość zapisywanego obrazu (0 do 100). Ten parametr wpływa tylko na zapisywanie w [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); dla wszystkich innych formatów jest ignorowany. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Zapisuje obraz do strumienia w określonym formacie i jakości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień, w którym zostanie zapisany obraz. |
| format | int | Format obrazu. |
| quality | int | Jakość zapisywanego obrazu (0 do 100). Ten parametr wpływa tylko na zapisywanie w [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); dla wszystkich innych formatów jest ignorowany. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Pobiera rozmiar obrazu.

**Zwraca:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Pobiera szerokość obrazu w pikselach.

**Zwraca:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Pobiera wysokość obrazu w pikselach.

**Zwraca:**
int