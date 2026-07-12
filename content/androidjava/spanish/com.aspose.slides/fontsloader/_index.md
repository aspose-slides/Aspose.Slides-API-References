---
title: FontsLoader
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Clase para cargar fuentes personalizadas definidas por el usuario.
type: docs
url: /es/com.aspose.slides/fontsloader/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Clase para cargar fuentes personalizadas definidas por el usuario. Debe usarse antes de crear cualquier objeto de presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Agrega carpetas adicionales para buscar fuentes. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Agrega una fuente a partir de los datos binarios |
| [getFontFolders()](#getFontFolders--) | Obtiene las carpetas de fuentes. |
| [clearCache()](#clearCache--) | Libera todas las fuentes personalizadas definidas por el usuario |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Agrega carpetas adicionales para buscar fuentes.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // carpetas para buscar fuentes
>  String[] folders = new String[] { dataDir };
>  // Cargar la carpeta de fuentes personalizadas
>  FontsLoader.loadExternalFonts(folders);
>  // Realizar algún trabajo y renderizar presentaciones/diapositivas
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Limpiar caché de fuentes
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| directories | java.lang.String[] | Directorios para leer fuentes adicionales. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Agrega una fuente a partir de los datos binarios

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Datos de la fuente |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Obtiene las carpetas de fuentes. Devuelve las carpetas que se han añadido con el método LoadExternalFonts, así como las carpetas de fuentes del sistema

**Devuelve:**
java.lang.String[] - array que contiene los nombres de las carpetas
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Libera todas las fuentes personalizadas definidas por el usuario

--------------------

Este método necesita limpiar la caché con fuentes personalizadas definidas por el usuario.