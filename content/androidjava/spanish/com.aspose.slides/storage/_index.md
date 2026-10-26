---
title: Storage
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un almacenamiento temporal de datos para .
type: docs
url: /es/com.aspose.slides/storage/
---
**Herencia:**
java.lang.Object
```
public final class Storage
```

Representa un almacenamiento temporal de datos para [WebDocument](../../com.aspose.slides/webdocument).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Storage()](#Storage--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Inserta el valor en el almacenamiento. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Obtiene los datos del almacenamiento. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina si el almacenamiento contiene un elemento con la clave especificada. |
### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

Inserta el valor en el almacenamiento.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Clave del valor. |
| value | TValue | Valor. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

Obtiene los datos del almacenamiento.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Clave del valor. |

**Devuelve:**
TValue - Valor de datos si está presente en la colección de datos, null de lo contrario.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

Determina si el almacenamiento contiene un elemento con la clave especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Clave del valor. |

**Devuelve:**
boolean - True si el almacenamiento contiene un elemento con la clave especificada, false de lo contrario.