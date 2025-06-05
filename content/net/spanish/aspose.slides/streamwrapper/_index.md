---  
title: StreamWrapper
second_title: Referencia de la API de Aspose.Slides para .NET  
description: Envoltorio de Aspose.IO.Stream para la interfaz COM.
type: docs  
weight: 10440  
url: /es/aspose.slides/streamwrapper/
---  

## Clase StreamWrapper  

Envoltorio de Aspose.IO.Stream para la interfaz COM.  

```csharp  
public class StreamWrapper : IStreamWrapper  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [AsIDisposable](../../aspose.slides/streamwrapper/asidisposable) { get; } | Permite obtener la interfaz base IDisposable. Solo lectura IDisposable. |  
| [CanRead](../../aspose.slides/streamwrapper/canread) { get; } | Obtiene un valor que indica si el flujo actual admite lectura. Booleano de solo lectura. |  
| [CanSeek](../../aspose.slides/streamwrapper/canseek) { get; } | Obtiene un valor que indica si el flujo actual admite búsqueda. Booleano de solo lectura. |  
| [CanWrite](../../aspose.slides/streamwrapper/canwrite) { get; } | Obtiene un valor que indica si el flujo actual admite escritura. Booleano de solo lectura. |  
| [Length](../../aspose.slides/streamwrapper/length) { get; } | Obtiene la longitud en bytes del flujo. Int64 de solo lectura. |  
| [Position](../../aspose.slides/streamwrapper/position) { get; } | Obtiene o establece la posición dentro del flujo actual. Int64 de solo lectura. |  
| [Stream](../../aspose.slides/streamwrapper/stream) { get; } | Obtiene un flujo. Flujo de solo lectura. |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [Close](../../aspose.slides/streamwrapper/close)() | Cierra el flujo actual y libera cualquier recurso. |  
| [Dispose](../../aspose.slides/streamwrapper/dispose)() | Elimina el objeto. |  
| [Flush](../../aspose.slides/streamwrapper/flush)() | Limpia todos los búferes para este flujo y causa que cualquier dato en búfer se escriba en el dispositivo subyacente. |  
| [Read](../../aspose.slides/streamwrapper/read)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo por el número de bytes leídos. |  
| [ReadByte](../../aspose.slides/streamwrapper/readbyte)() | Lee un byte del flujo y avanza la posición dentro del flujo un byte, o devuelve -1 si se encuentra al final del flujo. |  
| [Seek](../../aspose.slides/streamwrapper/seek)(long, SeekOrigin) | Establece la posición dentro del flujo actual |  
| [Write](../../aspose.slides/streamwrapper/write)(byte[], int, int) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo por el número de bytes escritos. |  
| [WriteByte](../../aspose.slides/streamwrapper/writebyte)(byte) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo un byte. |  

### Véase también  

* interfaz [IStreamWrapper](../istreamwrapper)  
* espacio de nombres [Aspose.Slides](../../aspose.slides)  
* ensamblaje [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  