---
title: IPresentationFactory
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Umožňuje vytvořit prezentaci pomocí rozhraní COM
type: docs
url: /cs/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Umožňuje vytvořit prezentaci pomocí rozhraní COM

## Metody

| Metoda | Popis |
| --- | --- |
| [createPresentation()](#createPresentation--) | Vytvoří novou prezentaci. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Vytvoří novou prezentaci s dalšími možnostmi načtení |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Získá informace o prezentaci ve zadaném souboru. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Získá informace o prezentaci ve zadaném proudu. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Načte existující prezentaci z pole |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Načte existující prezentaci z pole s dalšími možnostmi načtení |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Načte existující prezentaci z proudu |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Načte existující prezentaci z proudu s dalšími možnostmi načtení |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Načte existující prezentaci ze souboru |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Načte existující prezentaci z proudu s dalšími možnostmi načtení |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Získá surový text ze snímků |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Získá surový text ze snímků |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Získá surový text ze snímků |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Vytvoří novou prezentaci.

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nová prezentace

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Vytvoří novou prezentaci s dalšími možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nová prezentace

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Získá informace o prezentaci ve zvoleném souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Soubor prezentace. |

**Vrací:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Získá informace o prezentaci ve zvoleném proudu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Proud prezentace. |

**Vrací:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Načte existující prezentaci z pole

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Pole k načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Načte existující prezentaci z pole s dalšími možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Pole k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Načte existující prezentaci z proudu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud k načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Načte existující prezentaci z proudu s dalšími možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Načte existující prezentaci ze souboru

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Název souboru |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Načte existující prezentaci z proudu s dalšími možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Název souboru |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor |
| mode | int | Režim extrakce |

**Vrací:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud |
| mode | int | Režim extrakce |

**Vrací:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud |
| mode | int | Režim extrakce |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Vrací:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků