### jnitparams
---
https://pragmatists.github.io/JUnitParams/

```java
@RunWith(JUnitParamsRunner.class)
public class PersonTest {
  
  @Test
  @Parameters({"17, false",
    "22, true"})
  public void personIsAdult(intage, boolean valid) throws Exception {
    assertThat(new Person(age).isAdult(), is(valid));
  }
}
```

```
```

```
```


