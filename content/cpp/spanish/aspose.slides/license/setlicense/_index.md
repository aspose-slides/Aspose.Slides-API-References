---
title: SetLicense()
second_title: Referencia de API de Aspose.Slides para C++
description: Licencia el componente.
type: docs
weight: 14
url: /es/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) método

Licencia el componente.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |
## Observaciones



Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del ensamblado del componente.

3. La carpeta del ensamblado que llama el cliente.

4. La carpeta del ensamblado de entrada.

5. Un recurso incrustado en el ensamblado que llama el cliente.

**Nota:**En .NET Compact Framework, intenta encontrar la licencia solo en estas ubicaciones:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado que llama el cliente.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) método


Licencia el componente.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que contiene la licencia. |
## Observaciones



Use este método para cargar una licencia desde un flujo.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [License](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)