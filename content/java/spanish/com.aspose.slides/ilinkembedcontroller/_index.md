---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
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
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determina dónde debe almacenarse el objeto. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Devuelve una URL a un objeto externo. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Guarda el objeto externo. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Determina dónde debe almacenarse el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con diferentes id.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único durante toda la operación de guardado. |
| entityData | byte[] | Datos binarios del objeto. Este parámetro puede ser null, si los datos binarios del objeto aún no se han generado. |
| semanticName | java.lang.String | Algún texto corto que describa el significado del objeto. El controlador puede usarlo como parte del nombre del objeto externo, pero corresponde al despachador garantizar que los nombres sean únicos y contengan solo los caracteres permitidos. |
| contentType | java.lang.String | Tipo MIME del objeto. |
| recomendedExtension | java.lang.String | Extensión de nombre de archivo recomendada para este tipo MIME. |

**Devuelve:**
int - Decisión
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Devuelve una URL a un objeto externo. Este método siempre se llama si \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) devolvió [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) y puede llamarse si \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) devolvió [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) pero la incrustación es imposible. Puede llamarse múltiples veces para el mismo id de objeto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único durante toda la operación de guardado. |
| referrer | int | Id del objeto de referencia o 0, si el objeto es referenciado por el documento raíz. Puede usarse para generar un enlace relativo. |

**Devuelve:**
java.lang.String - URL del objeto externo o null si este objeto debe ser ignorado.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Guarda el objeto externo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int | Id del objeto. Este id es único durante toda la operación de guardado. |
| entityData | byte[] | Datos binarios del objeto. Este parámetro no puede ser null. |