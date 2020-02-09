# Crazy_English
Crazy English

Make English learning be fun!

## Todo

* Make Crazy English services
	* Query random vocabulary / conversation
	* Search
	* Find quick card...

## Split up even further

After a period of time, I felt that a set of vocabulary was too ineffective so I decided to break up the vocabulary further =))

### 400 conversation split by 50

https://github.com/soiqualang/crazy_english/tree/master/400%20conversation%20split%20by%2050

### 4000 Core English Vocabulary Words split by 50

https://github.com/soiqualang/crazy_english/tree/master/4000%20Core%20English%20Vocabulary%20Words%20split%20by%2050

***

## 400 crazy Vietnamese - English

`=RIGHT(chuỗi văn bản, LEN(chuỗi văn bản) - SEARCH(kí tự, chuỗi văn bản))`

> 400_crazy_english_trans.xlsx
`=RIGHT(A1,LEN(A1)-SEARCH(".",A1))`

https://quizlet.com/474345902/400-crazy-vietnamese-english-flash-cards/

## 4000 Core English Vocabulary Words

> 4000 Core English Vocabulary Words part 1

https://quizlet.com/_7ug179?x=1qqt&i=26wdm4

> 4000 Core English Vocabulary Words part 2

https://quizlet.com/_7ug24v?x=1qqt&i=26wdm4

> 4000 Core English Vocabulary Words part 3

https://quizlet.com/_7ug2dw?x=1qqt&i=26wdm4

> 4000 Core English Vocabulary Words part 4

https://quizlet.com/_7ug2ge?x=1qqt&i=26wdm4


> 3000-tu-tieng-anh-thong-dung-nhat.xlsx
```bash
=TRIM(A1)
=RIGHT(B1,LEN(B1)-SEARCH("/",B1))
=RIGHT(C1,LEN(C1)-SEARCH("/",C1))
```

`= IF ( COUNTIF ( phạm vi , giá trị ), "Có" , "Không" )`

```
=ISNUMBER(SEARCH("/",B1))
=IF(ISNUMBER(SEARCH("/",B1)),"Có","Không")
=IF(ISNUMBER(SEARCH("/",B1)),RIGHT(B1,LEN(B1)-SEARCH("/",B1)),RIGHT(B1,LEN(B1)-SEARCH(". ",B1)))
=IF(ISNUMBER(SEARCH("/",C1)),RIGHT(C1,LEN(C1)-SEARCH("/",C1)),C1)

=LEFT(B1,SEARCH(" ",B1))
```

Prepare data to make Semper card `Vietnamese - English`

https://quizlet.com/_7uevn2?x=1qqt&i=26wdm4


## Refereces

https://quantrimang.com/ham-right-cach-dung-ham-cat-chuoi-ky-tu-ben-phai-trong-excel-163300