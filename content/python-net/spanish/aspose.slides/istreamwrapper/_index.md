---
title: IStreamWrapper class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/istreamwrapper/
---
## IStreamWrapper clase

Aspose.IO.Stream envoltorio para la interfaz COM.

El tipo IStreamWrapper expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`stream`](/slides/python-net/es/aspose.slides/istreamwrapper/stream/) | Obtiene una secuencia.<br/>            Solo lectura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/es/aspose.slides/istreamwrapper/can_read/) | Obtiene un valor que indica si la secuencia actual admite lectura.<br/>            Solo lectura **bool**. |
| [`can_seek`](/slides/python-net/es/aspose.slides/istreamwrapper/can_seek/) | Obtiene un valor que indica si la secuencia actual admite búsqueda.<br/>            Solo lectura **bool**. |
| [`can_write`](/slides/python-net/es/aspose.slides/istreamwrapper/can_write/) | Obtiene un valor que indica si la secuencia actual admite escritura.<br/>            Solo lectura **bool**. |
| [`length`](/slides/python-net/es/aspose.slides/istreamwrapper/length/) | Obtiene la longitud en bytes de la secuencia.<br/>            Solo lectura **int**. |
| [`position`](/slides/python-net/es/aspose.slides/istreamwrapper/position/) | Obtiene la posición dentro de la secuencia actual.<br/>            Solo lectura **int**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`close(self)`](/slides/python-net/es/aspose.slides/istreamwrapper/close/#) | Cierra la secuencia actual y libera cualquier recurso. |
| [`flush(self)`](/slides/python-net/es/aspose.slides/istreamwrapper/flush/#) | Borra todos los búferes de esta secuencia y hace que los datos almacenados se escriban en el dispositivo subyacente. |
| [`read(self, buffer, offset, count)`](/slides/python-net/es/aspose.slides/istreamwrapper/read/#bytes-int-int) | Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia en el número de bytes leídos. |
| [`read_byte(self)`](/slides/python-net/es/aspose.slides/istreamwrapper/read_byte/#) | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| [`seek(self, offset, origin)`](/slides/python-net/es/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Establece la posición dentro de la secuencia actual |
| [`write(self, buffer, offset, count)`](/slides/python-net/es/aspose.slides/istreamwrapper/write/#bytes-int-int) | escribe una secuencia de bytes en la secuencia actual y avanza la posición actual dentro de esta secuencia en el número de bytes escritos. |
| [`write_byte(self, value)`](/slides/python-net/es/aspose.slides/istreamwrapper/write_byte/#int) | Escribe un byte en la posición actual de la secuencia y avanza la posición dentro de la secuencia en un byte. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)