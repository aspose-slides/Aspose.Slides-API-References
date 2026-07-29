---
title: Point()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Point-objekt och initierar dess X- och Y-koordinatvärden till 0.
type: docs
weight: 1
url: /sv/system.drawing/point/point/
---
## Point::Point() konstruktor

Skapar ett nytt [Point](../)-objekt och initierar dess X- och Y-koordinatvärden till 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) konstruktor

Skapar ett nytt [Point](../)-objekt och initierar det med de angivna värdena.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Värdet för X-koordinaten |
| y | int | Värdet för Y-koordinaten |

## Point::Point(const Size\&) konstruktor

Skapar ett nytt [Point](../)-objekt och initierar dess X- och Y-koordinatvärden med bredd- och höjdvärden från det specificerade [SizeF](../../sizef/)-objektet respektive.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Ett [SizeF](../../sizef/)-objekt vars bredd- och höjdvärden används för att initiera X- och Y-koordinatvärdena för det [Point](../)-objekt som skapas |

## Point::Point(int) konstruktor

Skapar ett nytt [Point](../)-objekt och initierar dess X-koordinatavärde med ett värde bildat av de högsta 16 bitarna i det angivna 32-bitars heltalet samt dess Y-koordinatavärde med ett värde bildat av de lägsta 16 bitarna i det angivna 32-bitars heltalet.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dw | int | Det 32-bitars heltal vars högsta 16 bitar anger X-koordinatavärdet och lägsta 16 bitar anger Y-koordinatavärdet för det objekt som skapas |

## Se även

* Klass [Point](../)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)