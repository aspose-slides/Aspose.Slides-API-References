---
title: ICustomXmlPartCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av anpassade xml-parts.
type: docs
url: /sv/com.aspose.slides/icustomxmlpartcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Representerar en samling av anpassade xml-delar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar elementet på det angivna indexet. |
| [add(byte[] xmlData)](#add-byte---) | Lägger till en ny anpassad xml-del. |
| [add(String xmlString)](#add-java.lang.String-) | Lägger till en ny anpassad xml-del. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Lägger till en ny anpassad xml-del. |
| [removeAt(int index)](#removeAt-int-) | Tar bort anpassad xml-del på det angivna indexet. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Returnerar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet att hämta. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Elementet på det angivna indexet.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlData | byte[] | Xml-data för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlString | java.lang.String | Xml-strängen för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream med xml-data för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort anpassad xml-del på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet att ta bort. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Den anpassade xml-delen att ta bort. |

**Returnerar:**
boolean - true om objektet tas bort framgångsrikt; annars false.
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.