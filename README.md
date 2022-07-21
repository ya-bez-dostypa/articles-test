## Добавление постов

<details><summary>Я разработчик и/или понимаю как пользоваться гитхабом</summary>
<p>

#### Я разработчик и/или понимаю как пользоваться гитхабом

</p>
</details>

<details><summary>Мне нужна подробная инструкция</summary>
<p>

- Создать отдельную ветку от main, в текстовом поле ввести название новой ветки, нажать на Create branch
 
![pr_creating](https://user-images.githubusercontent.com/48432436/165773036-c069375a-be64-4acc-9588-f7feff17f86d.png)

- Перейти в новую ветку и кликнуть 'Add file' => 'Upload files'

![file_upload](https://user-images.githubusercontent.com/48432436/165773878-ec09aa84-1e31-4bd3-9f5d-75bfa10ed0b5.png)

- Перетащить файл поста или папку с файлом в поле на новой странице. После успешной загрузки нажать зеленую кнопку 'Commit changes'
  - При создании нового поста важно убедиться, что папка с таким именем не существует в основной ветке, иначе существующий пост будет обновлен  ( за раз можно добавить не более 30 файлов)

![drag_n_drop](https://user-images.githubusercontent.com/48432436/165774478-9143844f-141a-4fda-8602-2b4c183768dc.png)

- Если все прошло успешно, то на экране появится соответствующее сообщение, в котором предлагается создать Pull Request. Кликаем зеленую кнопку 'Compare & pull request'

![create_pr](https://user-images.githubusercontent.com/48432436/165775602-7d316595-dc96-455a-8b18-aa0ca94afc08.PNG)

- В новом окне надо задать информацию о Pull Request. Поля заголовка и описания используются только для удобства редактора, они не играют абсолютно никакой роли в формировании поста. Те лейблы, которые будут проставлены в поле 'labels' в дальнейшем станут тегами поста. На данном этапе необязательно заполнять все как в последний раз, у вас еще будет возможно все отредактировать. После всех приготовлений кликаем зеленую кнопку 'Create pull request'

![Pr_desc](https://user-images.githubusercontent.com/48432436/165777031-a5195bf2-cd7a-465d-a010-487b23bc444d.PNG)

- В следующем окне отображается вся информация о вашем Pull Request, вы в любой момент можете его закрыть и вернуться позднее, прогресс не пропадет. Создание поста происходит после клика на кнопку 'Merge pull request'

</p>
</details>

## Обновление постов

<details><summary>Я разработчик и/или понимаю как пользоваться гитхабом</summary>
<p>

#### Обновление существующего поста
- Если вам надо обновить только теги, то можно использовать Pull Request, который создавался ранее для создания поста, в случае изменения тегов в этом PR они автоматически изменятся в посте. Для редактирования остальных полей необходимо пройти процедуру создания поста снова. При обновлении поста важно учитывать его расположение в основной ветке проекта. То есть, если файл поста, который вы хотите изменить, называется 'PostAboutForest.md' и находится в папке 'Forest', то в новой ветке он так же должен находится в папке 'Forest' и иметь названия 'PostAboutForest.md'. Остальные полностью действия аналогичны созданию поста

</p>
</details>


