# Issue 174

```bash
(! 555)-> clojure -M:poly test :dev :all
Projects to run tests from: development

Couldn't resolve libraries for the development project: java.lang.Exception: Unknown library type:
```

Because the following style of git deps does not work:

```clojure
io.github.seancorfield/deps-new {:git/sha "12510ba7ad0d0e00bef16666b92db340adeadcf1"}
```
