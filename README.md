# amarker

![](amarker-screenshot.png)

Android Marker

## Usage

```java
Amarker.from(context).on(view).center().mark();

Amarker.from(context).on(view).center().top().mark();
Amarker.from(context).on(view).center().bottom().mark();
Amarker.from(context).on(view).right().top().mark();
Amarker.from(context).on(view).left().top().mark();
Amarker.from(context).on(view).right().bottom().mark();
Amarker.from(context).on(view).left().bottom().mark();

Amarker.from(context).on(view).bg(gradientCircle).mark();
Amarker.from(context).on(view).fg(yellowExclamationMarkDrawable).bg(yellowGradientCircleDrawable).mark();
```
