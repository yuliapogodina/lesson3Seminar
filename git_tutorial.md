# Туториал по Git

## Как добавит СКВ (систему контроля версий) в ваш проект

Чтобы   добавить систему контроля версий в ваш проект, используйте следующую команду:

```
git init
```
---

## Как добавить изменения в git

Чтобы зафиксировать изменения, используйте следующую команду:
```
git commit -m "ваше сообщение"
```
***Перед тем ка зафиксировать изменения, их необходимо добавить в область подготовленных файлов***

Для этого необходимо использовать команду, с указанием имени файла :
```
git add file.txt
```
---

## Для контроля создания комита, и для просмотра списка комитов, используйте команду##
```
git log
```
---
### Могут потребоваться в работе команды из списка ниже 
* git status - проверяет статус репозитория, позволяет увидеть есть ли незакомиченные файлы;
* git diff - отображает изменения неподготовленные для фиксации по всему репозиторию;
* git stash - позволяет скрыть подготовленные для фиксации файлы, если нет уверенности что их стоит фиксировать в через сомит.

---
## При необходимости "откатить" последний комит, используйте команду:
```
git revert HEAD
```
