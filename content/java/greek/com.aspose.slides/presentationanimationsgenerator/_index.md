---
title: PresentationAnimationsGenerator
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει έναν δημιουργό των κινούμενων εικόνων στο .
type: docs
url: /el/com.aspose.slides/presentationanimationsgenerator/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

Αντιπροσωπεύει έναν δημιουργό των κινούμενων εικόνων στο [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Creates a new instance of the [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Dimension frameSize)](#PresentationAnimationsGenerator-java.awt.Dimension-) | Creates a new instance of the [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Dimension2D frameSize)](#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-) | Creates a new instance of the [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Disposes the instance of the [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [getFrameSize()](#getFrameSize--) | Gets the frame size. |
| [getDefaultDelay()](#getDefaultDelay--) | Gets or sets default delay time [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Gets or sets default delay time [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Get or sets if hidden slides should be included. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Get or sets if hidden slides should be included. |
| [getExportedSlides()](#getExportedSlides--) | Get the number of the exported slides count. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Set a new animation event. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Run the animation events generation for each slide. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Run the animation events generation for each slide. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Δημιουργεί μια νέα παρουσία του [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Το μέγεθος του πλαισίου θα οριστεί σύμφωνα με το [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) |

### PresentationAnimationsGenerator(Dimension frameSize) {#PresentationAnimationsGenerator-java.awt.Dimension-}
```
public PresentationAnimationsGenerator(Dimension frameSize)
```

Δημιουργεί μια νέα παρουσία του [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| frameSize | java.awt.Dimension | Το μέγεθος του πλαισίου. |

### PresentationAnimationsGenerator(Dimension2D frameSize) {#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-}
```
public PresentationAnimationsGenerator(Dimension2D frameSize)
```

Δημιουργεί μια νέα παρουσία του [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| frameSize | java.awt.geom.Dimension2D | Το μέγεθος του πλαισίου. |

### dispose() {#dispose--}
```
public final void dispose()
```

Καταστρέφει την παρουσία του [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

### getFrameSize() {#getFrameSize--}
```
public Dimension getFrameSize()
```

Λαμβάνει το μέγεθος του πλαισίου.

**Επιστρέφει:**
java.awt.Dimension
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Λαμβάνει ή ορίζει το προεπιλεγμένο χρόνο καθυστέρησης [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 δ
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Λαμβάνει ή ορίζει το προεπιλεγμένο χρόνο καθυστέρησης [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 δ
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

Λαμβάνει ή ορίζει εάν πρέπει να συμπεριληφθούν κρυφές διαφάνειες.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Λαμβάνει ή ορίζει εάν πρέπει να συμπεριληφθούν κρυφές διαφάνειες.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

Λαμβάνει τον αριθμό των εξαγόμενων διαφανειών.

**Επιστρέφει:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Ορίζει ένα νέο γεγονός κίνησης.

--------------------

> ```
> Presentation presentation = new Presentation("SimpleAnimations.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>          });
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Γεγονός κίνησης. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

Εκτελεί τη δημιουργία των γεγονότων κίνησης για κάθε διαφάνεια.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              animationsGenerator.setNewAnimation(animationPlayer ->
>              {
>                  // διαχειριστείτε τη νέα κίνηση
>              });
>              player.setFrameTick((sender, args) ->
>              {
>                  // διαχειριστείτε το frame tick μέσα στη νέα κίνηση
>              });
>              animationsGenerator.run(presentation.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

Εκτελεί τη δημιουργία των γεγονότων κίνησης για κάθε διαφάνεια.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.run(presentation.getSlides(), 33, (player, playerArgs) ->
>          {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>          });
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |