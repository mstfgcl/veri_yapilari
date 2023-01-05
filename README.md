# veri_yapilari/proje 1
## Insertion Sort aşamaları:
- ilk aşama      [22,27|16,2,18,6] -> 22<27 olduğu için bir değişim olmaz
- ikinci aşama   [22,27,16|2,18,6] -> [22,16,27],2,18,6 -> [16,22,27],2,18,6 
- üçüncü aşama   [16,22,27,2|18,6] -> [16,22,2,27],18,6 -> [16,2,22,27],18,6 -> [2,16,22,27],18,6
- dördüncü aşama [2,16,22,27,18|6] -> [2,16,22,18,27],6 -> [2,16,18,22,27],6 
- beşinci aşama  [2,16,18,22,27,6|]-> [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] -> [2,6,16,18,22,27] sıralama tamamlanır
## Big-O gösterimi:

O(n^2)

## Time Complexity:

Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer çünkü dizinin ortasındadır. [2,6,16,18,22,27]
