---
title: set_SeparatorCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'."
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) método

El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Comentarios

Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Ver también

* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)