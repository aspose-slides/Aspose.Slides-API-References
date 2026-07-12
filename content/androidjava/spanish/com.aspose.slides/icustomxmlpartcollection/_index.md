---
title: ICustomXmlPartCollection
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una colección de partes xml personalizadas.
type: docs
url: /es/com.aspose.slides/icustomxmlpartcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Representa una colección de partes xml personalizadas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [add(byte[] xmlData)](#add-byte---) | Agrega una nueva parte xml personalizada. |
| [add(String xmlString)](#add-java.lang.String-) | Agrega una nueva parte xml personalizada. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Agrega una nueva parte xml personalizada. |
| [removeAt(int index)](#removeAt-int-) | Elimina la parte xml personalizada en el índice especificado. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Elimina la primera aparición de un objeto específico de la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Devuelve el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice base cero del elemento a obtener. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - El elemento en el índice especificado.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Agrega una nueva parte xml personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlData | byte[] | Los datos xml de la nueva parte a añadir. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada creada.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Agrega una nueva parte xml personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlString | java.lang.String | La cadena xml de la nueva parte a añadir. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada creada.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Agrega una nueva parte xml personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | El inputStream con datos xml de la nueva parte a añadir. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada creada.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina la parte xml personalizada en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice base cero del elemento a eliminar. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Elimina la primera aparición de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La parte xml personalizada a eliminar. |

**Devuelve:**
boolean - true si el elemento se elimina correctamente; de lo contrario, false.
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los elementos de la colección.