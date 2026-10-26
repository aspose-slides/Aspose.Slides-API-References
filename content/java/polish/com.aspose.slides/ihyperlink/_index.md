---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /pl/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Reprezentuje hiperłącze.
## Metody

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | Zwraca typ akcji HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Określa zewnętrzny URL. Jeśli ta właściwość nie jest null, to właściwość TargetSlide staje się null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Reprezentuje hiperłącze ustawione dla tego fragmentu bez względu na rzeczywistą zawartość fragmentu. |
| [getTargetSlide()](#getTargetSlide--) | Jeśli HyperlinkEx wskazuje konkretny slajd, zwraca ten slajd. |
| [getTargetFrame()](#getTargetFrame--) | Zwraca ramkę w nadrzędnym zestawie ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Zwraca ramkę w nadrzędnym zestawie ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. |
| [getTooltip()](#getTooltip--) | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. |
| [getHistory()](#getHistory--) | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy przeglądanych hiperłączy po jego wywołaniu. |
| [setHistory(boolean value)](#setHistory-boolean-) | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy przeglądanych hiperłączy po jego wywołaniu. |
| [getHighlightClick()](#getHighlightClick--) | Określa, czy hiperłącze powinno być podświetlane po kliknięciu. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Określa, czy hiperłącze powinno być podświetlane po kliknięciu. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Określa, czy dźwięk powinien zostać zatrzymany po kliknięciu hiperłącza. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Określa, czy dźwięk powinien zostać zatrzymany po kliknięciu hiperłącza. |
| [getSound()](#getSound--) | Reprezentuje odtwarzany dźwięk hiperłącza. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Reprezentuje odtwarzany dźwięk hiperłącza. |
| [getColorSource()](#getColorSource--) | Reprezentuje źródło koloru hiperłącza — style lub format fragmentu. |
| [setColorSource(int value)](#setColorSource-int-) | Reprezentuje źródło koloru hiperłącza — style lub format fragmentu. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Określa, czy dwa obiekty Hyperlink są równe. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Zwraca typ akcji HyperLinkEx. Tylko do odczytu [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Zwraca:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Określa zewnętrzny URL. Jeśli ta właściwość nie jest null, to właściwość TargetSlide staje się null. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Reprezentuje hiperłącze ustawione dla tego fragmentu bez względu na rzeczywistą zawartość fragmentu.

PowerPoint zachowuje się specyficznie w odniesieniu do linków i odpowiadającego im tekstu w fragmencie. Umożliwia tworzenie tekstu dla hiperłącza w formie prawidłowego adresu URL, różnego od rzeczywistego adresu linku. W takim przypadku, gdy przeglądasz link w oknie edycji, zostanie on zmieniony, aby pasował do fragmentu tekstu. Ta właściwość reprezentuje pierwotną wartość hiperłącza.

**Zwraca:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Jeśli HyperlinkEx wskazuje konkretny slajd, zwraca ten slajd. Jeśli właściwość nie jest null, to właściwość ExternalUrl staje się null. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Zwraca ramkę w nadrzędnym zestawie ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Zwraca ramkę w nadrzędnym zestawie ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy przeglądanych hiperłączy po jego wywołaniu. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy przeglądanych hiperłączy po jego wywołaniu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Określa, czy hiperłącze powinno być podświetlane po kliknięciu. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Określa, czy hiperłącze powinno być podświetlane po kliknięciu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Określa, czy dźwięk powinien zostać zatrzymany po kliknięciu hiperłącza. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Określa, czy dźwięk powinien zostać zatrzymany po kliknięciu hiperłącza. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Reprezentuje odtwarzany dźwięk hiperłącza. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Pobierz pierwsze hiperłącze kształtu
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Wyodrębnij dźwięk hiperłącza jako tablicę bajtów
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Reprezentuje odtwarzany dźwięk hiperłącza. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Pobierz pierwsze hiperłącze kształtu
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Wyodrębnij dźwięk hiperłącza jako tablicę bajtów
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Reprezentuje źródło koloru hiperłącza — style lub format fragmentu. Odczyt/zapis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Zwraca:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Reprezentuje źródło koloru hiperłącza — style lub format fragmentu. Odczyt/zapis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Określa, czy dwa obiekty Hyperlink są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hiperłącze do porównania z bieżącym Hyperlinkiem. |

**Zwraca:**
boolean - **true** jeśli podane Hyperlink jest równe bieżącemu Hyperlinkowi; w przeciwnym razie **false**.