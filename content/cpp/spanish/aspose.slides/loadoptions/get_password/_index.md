---
title: get_Password()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene la contraseña. Lea System::String."
type: docs
weight: 105
url: /es/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() método


Obtiene la contraseña. Lea [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Observaciones


La contraseña. 

El siguiente código de ejemplo muestra cómo abrir un PowerPoint protegido con contraseña [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// trabajar con la presentación descifrada
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)