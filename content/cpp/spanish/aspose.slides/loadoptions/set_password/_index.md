---
title: set_Password()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece la contraseña. Escriba System::String."
type: docs
weight: 118
url: /es/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) método

Establece la contraseña. Escriba [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Observaciones

La contraseña. 

El siguiente código de ejemplo muestra cómo abrir un PowerPoint protegido con contraseña [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)