---
title: get_SeparatorCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'."
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() method


Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Observaciones


Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Véase también

* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)