---
title: Math
second_title: Aspose.Slides för C++ API-referens
description: Innehåller matematiska funktioner. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1782
url: /sv/system/math/
---
## Math struktur


Innehåller matematiska funktioner. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Math
```

## Metoder

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Returnerar det absoluta värdet av det angivna värdet. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Returnerar det absoluta värdet av ett värde som representeras av det angivna [Decimal](../decimal/)-objektet. |
| static **double** [Acos](./acos/)(**double**) | Beräknar arcuscosinus för det angivna värdet. |
| static **double** [Asin](./asin/)(**double**) | Beräknar arcussinus för det angivna värdet. |
| static **double** [Atan](./atan/)(**double**) | Beräknar arcustangens för det angivna värdet. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Beräknar arcustangens för kvoten av de angivna värdena. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Returnerar hela produkten av två 32-bit-heltal. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Returnerar det minsta heltalsvärdet som är större än eller lika med det angivna värdet. |
| static **double** [Ceiling](./ceiling/)(**double**) | Returnerar det minsta heltalsvärdet som är större än eller lika med det angivna värdet. |
| static **double** [Cos](./cos/)(**double**) | Beräknar cosinus för det angivna värdet. |
| static **double** [Cosh](./cosh/)(**double**) | Beräknar hyperbolisk cosinus för det angivna värdet. |
| static int [DivRem](./divrem/)(int, int, int\&) | Beräknar kvoten av två 32-bit-heltal och resten. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Beräknar kvoten av två 64-bit-heltal och resten. |
| static **double** [Exp](./exp/)(**double**) | Returnerar e-konstanten upphöjt till den angivna potensen. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Returnerar det största heltalsvärdet som är mindre än eller lika med det angivna värdet. |
| static **double** [Floor](./floor/)(**double**) | Returnerar det största heltalsvärdet som är mindre än eller lika med det angivna värdet. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Returnerar resten som uppkommer vid divisionen av ett angivet tal med ett annat angivet tal. |
| static **double** [Log](./log/)(**double**) | Returnerar den naturliga logaritmen för det angivna värdet. |
| static **double** [Log](./log/)(**double**, **double**) | Returnerar logaritmen för det angivna värdet i den angivna basen. |
| static **double** [Log10](./log10/)(**double**) | Returnerar bas-10-logaritmen för det angivna värdet. |
| static auto [Max](./max/)(T0, T1) | Returnerar det största värdet av två angivna numeriska värden. |
| static T0 [Max](./max/)(T0, T1) | Returnerar det största värdet av två angivna numeriska värden. |
| **float** [Max_](./max_/)(**float**, **float**) | Returnerar det största enkelprecisionsflyttalsvärdet av de två angivna. |
| **double** [Max_](./max_/)(**double**, **double**) | Returnerar det största dubbelprecisionsflyttalsvärdet av de två angivna. |
| static auto [Min](./min/)(T0, T1) | Returnerar det minsta värdet av två angivna numeriska värden. |
| static T0 [Min](./min/)(T0, T1) | Returnerar det minsta värdet av två angivna numeriska värden. |
| **float** [Min_](./min_/)(**float**, **float**) | Returnerar det minsta enkelprecisionsflyttalsvärdet av de två angivna. |
| **double** [Min_](./min_/)(**double**, **double**) | Returnerar det minsta dubbelprecisionsflyttalsvärdet av de två angivna. |
| static T [Modulus](./modulus/)(T, T) | Beräknar resten som uppkommer vid divisionen av ett angivet värde med ett annat angivet värde. |
| static **double** [Pow](./pow/)(**double**, **double**) | Returnerar det angivna värdet upphöjt till den angivna potensen. |
| static **double** [Round](./round/)(**double**) | Avrundar det angivna värdet till närmaste heltal. |
| static **double** [Round](./round/)(**double**, int) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste heltal. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Avrundar det angivna värdet till närmaste heltal. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste heltal. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestämmer tecknet för det angivna signerade heltalsvärdet. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestämmer tecknet för det angivna flyttalsvärdet. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Bestämmer tecknet för det angivna decimalvärdet. |
| static **double** [Sin](./sin/)(**double**) | Beräknar sinus för det angivna värdet. |
| static **double** [Sinh](./sinh/)(**double**) | Beräknar hyperbolisk sinus för det angivna värdet. |
| static **double** [Sqrt](./sqrt/)(**double**) | Returnerar kvadratroten av det angivna värdet. |
| static **double** [Tan](./tan/)(**double**) | Beräknar tangens för det angivna värdet. |
| static **double** [Tanh](./tanh/)(**double**) | Beräknar hyperbolisk tangens för det angivna värdet. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Returnerar [Decimal](../decimal/)-objektet som representerar ett värde vars heltalsdel är lika med den som representeras av det angivna [Decimal](../decimal/)-objektet, med alla decimaler borttagna. |
| static **double** [Truncate](./truncate/)(**double**) | Returnerar ett dubbelprecisionsflyttal som har heltalsdelen lika med den angivna värdet, med alla decimaler borttagna. |
## Fält

| Field | Description |
| --- | --- |
| static [E](./e/) | Basen för den naturliga logaritmen. |
| static [NaN](./nan/) | Representerar ett icke-tal (NaN) värde. |
| static [NegativeInfinity](./negativeinfinity/) | Representerar negativ oändlighet. |
| static [PI](./pi/) | Pi-konstanten. |
| static [PositiveInfinity](./positiveinfinity/) | Representerar positiv oändlighet. |
## Anmärkningar



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Skriv ut de absoluta värdena.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Skriv ut sinus av PI/2 och cosinus av PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Detta kodexempel ger följande utdata:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.Slides](../../)