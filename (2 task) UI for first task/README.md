# UI for Object Detection
Лабораторная работа <br />
**Фуряев Денис 401 группа ВМК**

:heavy_exclamation_mark: Для работы консольного приложения необходимо поместить файл с обученной моделью <br />(.onnx файл можно скачать тут: https://github.com/onnx/models/tree/master/vision/object_detection_segmentation/yolov4) <br /> в папку ObjectDetectionLib\assets\model 
 :heavy_exclamation_mark:

Необходимо предоставить пользователю приложение с графическим пользовательским интерфейсом для обнаружения известных объектов на изображениях в заданном каталоге и просмотра результатов. 

**Критерий выполнения:**  <br />
Разработано приложение WPF позволяющее пользователю: 

1) Выбрать в графическом интерфейсе каталог, содержащий изображения и начать классификацию  
2) Просматривать информацию про обнаруженные объект. Информация должна динамически обновляться после обнаружения каждого нового объекта. 
3) Прерывать процесс распознавания изображений нажатием на кнопку 
4) Выбирать тип объекта и просматривать все изображения с заданным типом. 

**Требования к реализации:** <br />
1) Обработка изображений выполняется  c применением библиотеки классов, разработанной при выполнении Задачи 1. Задача 1 должна остаться работоспособной! 
2) Обработка изображений должна выполняться параллельно с работой пользовательского интерфейса. Пользовательский интерфейс не должен "зависать" пока идёт анализ изображений. 
3) Пользователю доступны для выбора все распознанные типы. При выборе определенного типа в окне приложения отображаются все изображения объектов этого типа.  Список изображений пополняется по мере распознавания файлов. 


**Пример работы пользовательского интерфейса:**


![image](https://user-images.githubusercontent.com/65111871/138114574-f96f2389-5e78-43a5-bd1f-738b351b3e34.png)
