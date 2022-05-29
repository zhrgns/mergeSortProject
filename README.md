# MERGE SORT PROJECT for PATIKA.DEV
---
## [16,21,11,8,12,22] >> Verilen dizinin Merge Sort dizilimi


* Dizi ikiye bölerek yeniden yazılır.
```
[16,21,11]    [8,12,22]
```

* Dizi ikiye bölerek yeniden yazılır.

```
[16]    [21,11]    [8]    [12,22]
```

* Dizi ikiye bölerek yeniden yazılır. Ve bölme tamamlanır.Artık dizilebilece ikili ve tekli elementler var.

```
[16]   [[21] [11]]    [[8] [12]]   [22]
```

* İkili parçalar kendi içinde dizilerek elementler tekrar mergelenmeye başlanır.

```
[16]  [11,21]  [8]  [12,22]
   \   /         \  /
 [11,16,21]     [8,12,22]
          \     /        
     [8,11,12,16,21,22]
```

* İşlem tamamlandı.

---

## Big O'Notation 


    O(nlogn)

---
### License
[MIT](https://choosealicense.com/licenses/mit/)
