---
title: BulletFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/bulletformat/
---

## BulletFormat class

 Represents paragraph bullet formatting properties.
 
| [applyDefaultParagraphIndentsShifts] () Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Calling this function doesn't matter and throw InvalidOperationException in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception); or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |


---


| [getChar] () Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |

### Result
char


---


| [getColor] () Returns the color format of a bullet of a paragraph with no inheritance. Read-only IColorFormat. |

### Result
[ColorFormat]


---


| [getEffective] () Gets effective bullet formatting data with the inheritance applied. |

### Result
[BulletFormatEffectiveData]


---


| [getFont] () Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |

### Result
[FontData]


---


| [getHeight] () Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |

### Result
float


---


| [getNumberedBulletStartWith] () Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |

### Result
short


---


| [getNumberedBulletStyle] () Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |

### Result
byte


---


| [getPicture] () Returns the picture used as a bullet in a paragraph with no inheritance. Read-only ISlidesPicture. |

### Result
[Picture]


---


| [getType] () Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |

### Result
byte


---


| [getVersion] ()  |

### Result
long


---


| [isBulletHardColor] () Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |

### Result
byte


---


| [isBulletHardFont] () Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |

### Result
byte


---


| [setBulletHardColor] ([byte]) Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |


---


| [setBulletHardFont] ([byte]) Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |


---


| [setChar] ([char]) Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |


---


| [setFont] ([FontData]) Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |


---


| [setHeight] ([float]) Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |


---


| [setNumberedBulletStartWith] ([short]) Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |


---


| [setNumberedBulletStyle] ([byte]) Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |


---


| [setType] ([byte]) Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |


---


