---
title: StreamWrapper class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/streamwrapper/
---
## StreamWrapper clase

Aspose.IO.Stream wrapper para la interfaz COM.

El tipo StreamWrapper expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/es/aspose.slides/streamwrapper/stream/) | Obtiene un flujo.<br/>            Sólo lectura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/es/aspose.slides/streamwrapper/can_read/) | Obtiene un valor que indica si el flujo actual admite lectura.<br/>            Sólo lectura **bool**. |
| [`can_seek`](/slides/python-net/es/aspose.slides/streamwrapper/can_seek/) | Obtiene un valor que indica si el flujo actual admite búsqueda.<br/>            Sólo lectura **bool**. |
| [`can_write`](/slides/python-net/es/aspose.slides/streamwrapper/can_write/) | Obtiene un valor que indica si el flujo actual admite escritura.<br/>            Sólo lectura **bool**. |
| [`length`](/slides/python-net/es/aspose.slides/streamwrapper/length/) | Obtiene la longitud en bytes del flujo.<br/>            Sólo lectura **int**. |
| [`position`](/slides/python-net/es/aspose.slides/streamwrapper/position/) | Obtiene o establece la posición dentro del flujo actual.<br/>            Sólo lectura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/es/aspose.slides/streamwrapper/close/#) | Cierra el flujo actual y libera cualquier recurso. |
| [`flush(self)`](/slides/python-net/es/aspose.slides/streamwrapper/flush/#) | Borra todos los buffers de este flujo y hace que los datos almacenados se escriban en el dispositivo subyacente. |
| [`read(self, buffer, offset, count)`](/slides/python-net/es/aspose.slides/streamwrapper/read/#bytes-int-int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| [`read_byte(self)`](/slides/python-net/es/aspose.slides/streamwrapper/read_byte/#) | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| [`seek(self, offset, origin)`](/slides/python-net/es/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Establece la posición dentro del flujo actual |
| [`write(self, buffer, offset, count)`](/slides/python-net/es/aspose.slides/streamwrapper/write/#bytes-int-int) | escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| [`write_byte(self, value)`](/slides/python-net/es/aspose.slides/streamwrapper/write_byte/#int) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)