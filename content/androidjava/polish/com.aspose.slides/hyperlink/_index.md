---
title: Hyperlink
second_title: Aspose.Slides dla Androida przy użyciu dokumentacji Java API
description: Reprezentuje hiperłącze.
type: docs
url: /pl/com.aspose.slides/hyperlink/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Reprezentuje hiperłącze.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Tworzy instancję hiperłącza. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Tworzy instancję hiperłącza, które wskazuje na określony slajd. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Tworzy instancję hiperłącza przy użyciu innego hiperłącza jako źródła, nadpisując właściwości dodatkowe. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Zwraca specjalne hiperłącze „do nothing”. |
| [getMedia()](#getMedia--) | Zwraca specjalne hiperłącze „play mediafile”. |
| [getNextSlide()](#getNextSlide--) | Zwraca hiperłącze do następnego slajdu. |
| [getPreviousSlide()](#getPreviousSlide--) | Zwraca hiperłącze do poprzedniego slajdu. |
| [getFirstSlide()](#getFirstSlide--) | Zwraca hiperłącze do pierwszego slajdu prezentacji. |
| [getLastSlide()](#getLastSlide--) | Zwraca hiperłącze do ostatniego slajdu prezentacji. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Zwraca hiperłącze do ostatnio oglądanego slajdu. |
| [getEndShow()](#getEndShow--) | Zwraca hiperłącze kończące pokaz. |
| [getActionType()](#getActionType--) | Zwraca typ akcji hiperłącza. |
| [getExternalUrl()](#getExternalUrl--) | Określa zewnętrzny URL. |
| [getTargetSlide()](#getTargetSlide--) | Jeśli hiperłącze wskazuje określony slajd, zwraca ten slajd. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Reprezentuje hiperłącze ustawione dla tej części bez względu na rzeczywistą treść części. |
| [getTargetFrame()](#getTargetFrame--) | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. |
| [getTooltip()](#getTooltip--) | Zwraca ciąg znaków, który może być wyświetlony w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Zwraca ciąg znaków, który może być wyświetlony w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. |
| [getHistory()](#getHistory--) | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu. |
| [setHistory(boolean value)](#setHistory-boolean-) | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu. |
| [getHighlightClick()](#getHighlightClick--) | Określa, czy hiperłącze ma być podświetlane po kliknięciu. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Określa, czy hiperłącze ma być podświetlane po kliknięciu. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza. |
| [getSound()](#getSound--) | Reprezentuje odtwarzany dźwięk hiperłącza. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Reprezentuje odtwarzany dźwięk hiperłącza. |
| [getColorSource()](#getColorSource--) | Reprezentuje źródło koloru hiperłącza – style lub format części. |
| [setColorSource(int value)](#setColorSource-int-) | Reprezentuje źródło koloru hiperłącza – style lub format części. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwie instancje Hyperlink są równe. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Określa, czy dwie instancje Hyperlink są równe. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dwa hiperłącza pod kątem równości. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testuje dwa hiperłącza pod kątem nierówności. |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych, takich jak tablica haszująca. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Tworzy instancję hiperłącza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Tworzy instancję hiperłącza, które wskazuje na określony slajd. Uwaga: utworzone hiperłącze powinno być przypisane do obiektu z tej samej prezentacji, w przeciwnym razie link zostanie zapisany jako NoAction.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd docelowy. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Tworzy instancję hiperłącza przy użyciu innego hiperłącza jako źródła, nadpisując właściwości dodatkowe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hiperłącze źródłowe |
| targetFrame | java.lang.String | Rama docelowa |
| tooltip | java.lang.String | Tekst podpowiedzi |
| history | boolean | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu. |
| stopSoundsOnClick | boolean | Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza. |
| highlightClick | boolean | Określa, czy hiperłącze ma być podświetlane po kliknięciu. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Zwraca specjalne hiperłącze „do nothing”. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Zwraca specjalne hiperłącze „play mediafile”. Używane w AudioFrame i VideoFrame. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Zwraca hiperłącze do następnego slajdu. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Zwraca hiperłącze do poprzedniego slajdu. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Zwraca hiperłącze do pierwszego slajdu prezentacji. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Zwraca hiperłącze do ostatniego slajdu prezentacji. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Zwraca hiperłącze do ostatnio oglądanego slajdu. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Zwraca hiperłącze kończące pokaz. Tylko do odczytu [Hyperlink](../../com.aspose.slides/hyperlink).

**Zwraca:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Zwraca typ akcji hiperłącza. Tylko do odczytu [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Zwraca:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Określa zewnętrzny URL. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Jeśli hiperłącze wskazuje określony slajd, zwraca ten slajd. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Reprezentuje hiperłącze ustawione dla tej części bez względu na rzeczywistą treść części.

PowerPoint zachowuje się specyficznie wobec łączy i odpowiadającego im tekstu w części. Umożliwia stworzenie tekstu dla hiperłącza w formie prawidłowego URL, różnego od rzeczywistego adresu linku. W takim wypadku, gdy przeglądasz link w oknie edycji, zostanie on zmieniony, aby pasował do części tekstowej. Ta właściwość reprezentuje pierwotną wartość hiperłącza.

**Zwraca:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. Tylko do odczytu/zapisu String.

**Zwraca:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. Tylko do odczytu/zapisu String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Zwraca ciąg znaków, który może być wyświetlony w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Zwraca ciąg znaków, który może być wyświetlony w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Określa, czy hiperłącze ma być podświetlane po kliknięciu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Określa, czy hiperłącze ma być podświetlane po kliknięciu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Reprezentuje odtwarzany dźwięk hiperłącza. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Wyodrębnij dźwięk hiperłącza do tablicy bajtów
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
public final void setSound(IAudio value)
```

Reprezentuje odtwarzany dźwięk hiperłącza. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Wyodrębnij dźwięk hiperłącza do tablicy bajtów
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
public final int getColorSource()
```

Reprezentuje źródło koloru hiperłącza – style lub format części. Odczyt/zapis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Zwraca:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Reprezentuje źródło koloru hiperłącza – style lub format części. Odczyt/zapis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy dwie instancje Hyperlink są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Hiperłącze do porównania z bieżącym Hyperlink. |

**Zwraca:**
boolean – **true**, jeśli podane Hyperlink jest równe bieżącemu Hyperlink; w przeciwnym razie, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Określa, czy dwie instancje Hyperlink są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hiperłącze do porównania z bieżącym Hyperlink. |

**Zwraca:**
boolean – **true**, jeśli podane Hyperlink jest równe bieżącemu Hyperlink; w przeciwnym razie, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Testuje dwa hiperłącza pod kątem równości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Pierwsze hiperłącze do przetestowania. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Drugie hiperłącze do przetestowania. |

**Zwraca:**
boolean – **true**, jeśli hiperłącza są równe.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Testuje dwa hiperłącza pod kątem nierówności.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Pierwsze hiperłącze do przetestowania. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Drugie hiperłącze do przetestowania. |

**Zwraca:**
boolean – **false**, jeśli hiperłącza są równe.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych, takich jak tablica haszująca.

**Zwraca:**
int – kod skrótu dla adresu URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject