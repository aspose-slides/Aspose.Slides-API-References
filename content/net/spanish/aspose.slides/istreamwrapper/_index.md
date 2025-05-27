---
title: IStreamWrapper
second_title: Aspose.Slides para .NET Referencia de API
description: Envoltorio Aspose.IO.Stream para la interfaz COM.
type: docs
weight: 6910
url: /es/aspose.slides/istreamwrapper/
---

## Interfaz IStreamWrapper

Envoltorio Aspose.IO.Stream para la interfaz COM.

```csharp
public interface IStreamWrapper : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIDisposable](../../aspose.slides/istreamwrapper/asidisposable) { get; } | Permite obtener la interfaz base IDisposable. Solo lectura IDisposable. |
| [CanRead](../../aspose.slides/istreamwrapper/canread) { get; } | Obtiene un valor que indica si la corriente actual admite la lectura. Solo lectura Boolean. |
| [CanSeek](../../aspose.slides/istreamwrapper/canseek) { get; } | Obtiene un valor que indica si la corriente actual admite la búsqueda. Solo lectura Boolean. |
| [CanWrite](../../aspose.slides/istreamwrapper/canwrite) { get; } | Obtiene un valor que indica si la corriente actual admite la escritura. Solo lectura Boolean. |
| [Length](../../aspose.slides/istreamwrapper/length) { get; } | Obtiene la longitud en bytes de la corriente. Solo lectura Int64. |
| [Position](../../aspose.slides/istreamwrapper/position) { get; } | Obtiene la posición dentro de la corriente actual. Solo lectura Int64. |
| [Stream](../../aspose.slides/istreamwrapper/stream) { get; } | Obtiene una corriente. Solo lectura Stream. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Close](../../aspose.slides/istreamwrapper/close)() | Cierra la corriente actual y libera cualquier recurso. |
| [Flush](../../aspose.slides/istreamwrapper/flush)() | Borra todos los búferes para esta corriente y provoca que cualquier dato en búfer sea escrito en el dispositivo subyacente. |
| [Read](../../aspose.slides/istreamwrapper/read)(byte[], int, int) | Lee una secuencia de bytes de la corriente actual y avanza la posición dentro de la corriente por el número de bytes leídos. |
| [ReadByte](../../aspose.slides/istreamwrapper/readbyte)() | Lee un byte de la corriente y avanza la posición dentro de la corriente en un byte, o devuelve -1 si está al final de la corriente. |
| [Seek](../../aspose.slides/istreamwrapper/seek)(long, SeekOrigin) | Establece la posición dentro de la corriente actual. |
| [Write](../../aspose.slides/istreamwrapper/write)(byte[], int, int) | Escribe una secuencia de bytes en la corriente actual y avanza la posición actual dentro de esta corriente por el número de bytes escritos. |
| [WriteByte](../../aspose.slides/istreamwrapper/writebyte)(byte) | Escribe un byte en la posición actual de la corriente y avanza la posición dentro de la corriente en un byte. |

### Véase También

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->