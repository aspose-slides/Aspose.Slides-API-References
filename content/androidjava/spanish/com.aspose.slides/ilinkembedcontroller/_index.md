---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /es/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Interfaz de devolución de llamada utilizada para determinar cómo debe procesarse el objeto durante el guardado.

## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determina dónde se debe almacenar el objeto. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Determina dónde se debe almacenar el objeto. Este método se llama una vez para cada id de objeto. No se garantiza que no existan dos objetos con los mismos datos, semanticName y contentType pero con id diferente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único en toda la operación de guardado. |
| entityData | byte[] | Datos binarios del objeto. Este parámetro puede ser nulo, si los datos binarios del objeto aún no se han generado. |
| semanticName | java.lang.String | Algún texto corto que describa el significado del objeto. El controlador puede usarlo como parte del nombre del objeto externo, pero corresponde al despachador garantizar que los nombres sean únicos y contengan solo caracteres permitidos. |
| contentType | java.lang.String | Tipo MIME del objeto. |
| recomendedExtension | java.lang.String | Extensión de nombre de archivo recomendada para este tipo MIME. |

**Devuelve:**
int - Decisión

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Devuelve una URL a un objeto externo. Este método siempre se llama si #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) devolvió [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) y puede ser llamado si #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) devolvió [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) pero la incrustación es imposible. Puede llamarse múltiples veces para el mismo id de objeto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único en toda la operación de guardado. |
| referrer | int | Id del objeto que hace referencia o 0, si el objeto es referenciado por el documento raíz. Puede usarse para generar un enlace relativo. |

**Devuelve:**
java.lang.String - URL del objeto externo o nulo si este objeto debe ser ignorado.

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Guarda el objeto externo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único en toda la operación de guardado. |
| entityData | byte[] | Datos binarios del objeto. Este parámetro no puede ser nulo. |