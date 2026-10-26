---
title: SetWriteProtection()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la protección de escritura para esta presentación con la contraseña especificada.
type: docs
weight: 131
url: /es/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) método

Establece la protección de escritura para esta presentación con la contraseña especificada.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña. |

## Observaciones

El siguiente código de ejemplo muestra cómo establecer una protección de escritura en una presentación. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)