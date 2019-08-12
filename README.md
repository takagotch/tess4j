### tess4j
---
https://github.com/nguyenq/tess4j

```java
// src/main/java/net/sourceforge/tes4j/Word.java
package net.sourceforge.tess4j;

import java.awt.Rectangle;

public class Word {
  private final String text;
  private final float confidence;
  private final Rectangle rect;
  
  public Word(String text, float confidence, Rectangle boundingBox) {
    this.text = text;
    this.confidence = confidence;
    this.rect = boundingBox;
  }
}
```

```
```

```
```
