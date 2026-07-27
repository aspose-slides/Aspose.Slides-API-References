---
title: Rectangle
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma área retangular de uma imagem definida pelas coordenadas inteiras X e Y de seu canto superior esquerdo e sua largura e altura. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 235
url: /pt/system.drawing/rectangle/
---
## Rectangle classe

Representa uma área retangular de uma imagem definida pelos coordenadas inteiras X e Y de seu canto superior esquerdo e sua largura e altura. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos desse tipo.

```cpp
class Rectangle
```

## Métodos

| Method | Descrição |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Constrói um objeto [Rectangle](./) a partir do objeto [RectangleF](../rectanglef/) especificado, arredondando os valores de localização e tamanho do objeto [RectangleF](../rectanglef/) para os próximos valores inteiros superiores. |
| **bool** [Contains](./contains/)(int, int) const | Determina se o ponto especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Determina se o ponto especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Determina se o retângulo especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Determina se os retângulos representados pelo objeto atual e pelo objeto especificado são idênticos. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Constrói um novo objeto [Rectangle](./) que representa um retângulo com as localizações das bordas especificadas. |
| int [get_Bottom](./get_bottom/)() const | Retorna a coordenada y da borda inferior do retângulo representado pelo objeto atual. |
| int [get_Height](./get_height/)() const | Retorna a altura do retângulo representado pelo objeto atual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se as coordenadas X e Y do canto superior esquerdo do retângulo representado pelo objeto atual, bem como sua largura e altura, têm valores iguais a 0. |
| int [get_Left](./get_left/)() const | Retorna a coordenada X da borda esquerda do retângulo representado pelo objeto atual. |
| [Point](../point/) [get_Location](./get_location/)() const | Retorna uma instância da classe [Point](../point/) que especifica a localização do canto superior esquerdo do retângulo representado pelo objeto atual. |
| int [get_Right](./get_right/)() const | Retorna a coordenada X da borda direita do retângulo representado pelo objeto atual. |
| [Size](../size/) [get_Size](./get_size/)() const | Retorna uma instância da classe [Size](../size/) que especifica a largura e a altura do retângulo representado pelo objeto atual. |
| int [get_Top](./get_top/)() const | Retorna a coordenada Y da borda superior do retângulo representado pelo objeto atual. |
| int [get_Width](./get_width/)() const | Retorna a largura do retângulo representado pelo objeto atual. |
| int [get_X](./get_x/)() const | Retorna a coordenada X do canto superior esquerdo do retângulo representado pelo objeto atual. |
| int [get_Y](./get_y/)() const | Retorna a coordenada Y do canto superior esquerdo do retângulo representado pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash do objeto atual. |
| void [Inflate](./inflate/)(int, int) | Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores de largura e altura do objeto de tamanho especificado, respectivamente. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Aumenta a largura e a altura do retângulo representado pelo objeto especificado, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Substitui o retângulo representado pelo objeto atual pelo retângulo resultante da interseção com o retângulo representado pelo objeto especificado. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Retorna um retângulo que é o resultado da interseção dos retângulos especificados. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Determina se os retângulos representados pelos objetos atual e especificado intersectam. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Desloca a posição do retângulo representado pelo objeto atual pelos valores especificados. |
| void [Offset](./offset/)(int, int) | Desloca a posição do retângulo representado pelo objeto atual pelos valores especificados. |
|  [operator RectangleF](./operator_rectanglef/)() const | Retorna um objeto [RectangleF](../rectanglef/) que representa um retângulo equivalente ao retângulo representado pelo objeto atual. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Sempre retorna true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Sempre retorna false. |
|  [Rectangle](./rectangle/)() | Constrói uma nova instância do objeto [Rectangle](./) que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0. |
|  [Rectangle](./rectangle/)(int, int, int, int) | Constrói uma nova instância do objeto [Rectangle](./) que representa um retângulo com as coordenadas especificadas do canto superior esquerdo e largura e altura. |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Constrói uma nova instância do objeto [Rectangle](./) que representa um retângulo cujas coordenadas do canto superior esquerdo são especificadas como uma instância da classe [Point](../point/) e sua largura e altura como uma instância da classe [Size](../size/). |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Constrói uma nova instância do objeto [Rectangle](./) que representa o retângulo equivalente ao especificado. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Constrói um objeto [Rectangle](./) a partir do objeto [RectangleF](../rectanglef/) especificado, arredondando os valores de localização e tamanho do objeto [RectangleF](../rectanglef/) para os valores inteiros mais próximos. |
| void [set_Height](./set_height/)(int) | Define a altura do retângulo representado pelo objeto atual. |
| void [set_Location](./set_location/)([Point](../point/)) | Define a localização do canto superior esquerdo do retângulo representado pelo objeto atual. |
| void [set_Size](./set_size/)([Size](../size/)) | Define a largura e a altura do retângulo representado pelo objeto atual. |
| void [set_Width](./set_width/)(int) | Define a largura do retângulo representado pelo objeto atual. |
| void [set_X](./set_x/)(int) | Define a coordenada X do canto superior esquerdo do retângulo representado pelo objeto atual. |
| void [set_Y](./set_y/)(int) | Define a coordenada Y do canto superior esquerdo do retângulo representado pelo objeto atual. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em string do objeto atual. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Constrói um objeto [Rectangle](./) a partir do objeto [RectangleF](../rectanglef/) especificado, truncando os valores de localização e tamanho do objeto [RectangleF](../rectanglef/) para os próximos valores inteiros inferiores. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Retorna um retângulo que é o resultado da união dos retângulos especificados. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Um retângulo vazio, ou seja, um retângulo cujas coordenadas de localização e tamanho têm valores zero. |

## Ver também

* Namespace [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)