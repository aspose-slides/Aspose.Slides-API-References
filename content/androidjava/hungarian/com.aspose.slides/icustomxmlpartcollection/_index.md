---
title: ICustomXmlPartCollection
second_title: Aspose.Slides Androidhoz – Java API referenciája
description: Testreszabott xml részek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icustomxmlpartcollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

A testreszabott xml részek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az adott indexű elemet. |
| [add(byte[] xmlData)](#add-byte---) | Új testreszabott xml részt ad hozzá. |
| [add(String xmlString)](#add-java.lang.String-) | Új testreszabott xml részt ad hozzá. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Új testreszabott xml részt ad hozzá. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a testreszabott xml részt a megadott indexnél. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Visszaadja az adott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem lekéréséhez használandó nullártól induló index. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Az adott indexű elem.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Új testreszabott xml részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlData | byte[] | Az új rész hozzáadandó xml adatai. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott xml rész.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Új testreszabott xml részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlString | java.lang.String | Az új rész hozzáadandó xml karakterlánca. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott xml rész.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Új testreszabott xml részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputStream | java.io.InputStream | Az új rész hozzáadandó xml adatot tartalmazó inputStream. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott xml rész.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a testreszabott xml részt a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullártól induló indexe. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Az eltávolítandó testreszabott xml rész. |

**Visszatérési érték:**
boolean - true, ha az elem sikeresen eltávolításra került; egyébként false.
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet a gyűjteményből.