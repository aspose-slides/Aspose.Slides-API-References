---
title: ICustomXmlPartCollection
second_title: Aspose.Slides Java API referencia
description: Egyedi XML részek gyűjteményét jelenti.
type: docs
url: /hu/com.aspose.slides/icustomxmlpartcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

A testreszabott XML részek gyűjteményét jelenti.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [add(byte[] xmlData)](#add-byte---) | Új egyéni XML részt ad hozzá. |
| [add(String xmlString)](#add-java.lang.String-) | Új egyéni XML részt ad hozzá. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Új egyéni XML részt ad hozzá. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű egyéni XML részt. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Visszaadja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérdezendő elem nulla alapú indexe. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - A megadott indexű elem.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlData | byte[] | Az új részhez hozzáadandó XML adatok. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlString | java.lang.String | Az új részhez hozzáadandó XML karakterlánc. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputStream | java.io.InputStream | Az új részhez hozzáadandó XML adatokat tartalmazó inputStream. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű egyéni XML részt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulla alapú indexe. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Eltávolítja egy adott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Az eltávolítandó egyéni XML rész. |

**Visszatérési érték:**
boolean - true, ha az elemet sikeresen eltávolították; egyébként false.
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.