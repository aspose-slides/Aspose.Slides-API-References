---
title: CreateFileStreamWrapper()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea FileStream con la ruta especificada y el modo de creación.
type: docs
weight: 14
url: /es/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) method


Crea FileStream con la ruta especificada y el modo de creación.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nombre de archivo [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modo de archivo [System::IO::FileMode](../../../system.io/filemode/) |

### Valor devuelto

Wrapper de flujo para la interfaz COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) method


Crea FileStream con la ruta especificada, el modo de creación y el permiso de lectura/escritura.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nombre de archivo [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Modo de archivo [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Acceso al archivo [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Valor devuelto

Wrapper de flujo para la interfaz COM [IStreamWrapper](../../istreamwrapper/)

## Ver también

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)