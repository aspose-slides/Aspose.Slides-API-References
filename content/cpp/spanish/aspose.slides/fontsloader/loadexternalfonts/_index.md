---
title: LoadExternalFonts()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega carpetas adicionales para buscar fuentes.
type: docs
weight: 1
url: /es/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) método


Agrega carpetas adicionales para buscar fuentes.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Directorios para leer fuentes adicionales. |
## Observaciones



El siguiente ejemplo muestra cómo cargar fuentes personalizadas desde .TTF 
```cpp
// La ruta al directorio de documentos.
System::String dataDir = u"C:\\";

// carpetas para buscar fuentes
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Cargar las fuentes del directorio de fuentes personalizadas
FontsLoader::LoadExternalFonts(folders);

// Realizar algún trabajo y renderizar la presentación/diapositivas
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Limpiar la caché de fuentes
FontsLoader::ClearCache();
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [FontsLoader](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)