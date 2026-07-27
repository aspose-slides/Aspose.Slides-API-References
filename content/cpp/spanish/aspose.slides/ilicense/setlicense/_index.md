---
title: SetLicense()
second_title: Referencia de API de Aspose.Slides para C++
description: Licencia el componente.
type: docs
weight: 1
url: /es/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) método


Licencia el componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incorporado. Use una cadena vacía para cambiar al modo de evaluación. |
## Observaciones



Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del ensamblado del componente.

3. La carpeta del ensamblado que llama el cliente.

4. La carpeta del ensamblado de entrada.

5. Un recurso incorporado en el ensamblado que llama el cliente.

**Nota:** En el .NET Compact Framework, intenta encontrar la licencia solo en estas ubicaciones:

1. Ruta explícita.

2. Un recurso incorporado en el ensamblado que llama el cliente.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incorporados del ensamblado que llama. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) método


Licencia el componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que contiene la licencia. |
## Observaciones



Utilice este método para cargar una licencia desde un flujo.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ILicense](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)