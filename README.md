Тестовое задание: автосервис

![](demo.png)

https://rails-production-8bd7.up.railway.app/

Задача:
- спроектировать и реализовать приложение, позволяющее вести учёт заказов в автосервисе
- опубликовать приложение на сервисе heroku.

Требования к реализации:
- использовать сущности:
	+ заказ
		* дата создания
		* имя заказчика
	+ услуга
		* название
	+ категория услуги
		* название
	+ исполнитель услуги
		* имя
- в заказе может быть несколько услуг
- при продаже услуги за ней закрепляется исполнитель, выбираемый из персонала автосервиса

Требования к функционалу:
- возможность создания, получения, редактирования, удаления для всех сущностей через интерфейс приложения
- сортировка и фильтрация списка заказов по собственным полям, а так же по полям связанных сущностей: исполнитель услуги, категория услуги
- возможность выгрузки результатов сортировки в excel, использовать гем caxlsx_rails

Требования к инструментам:
- ruby v 2.6+
- rails v 6+