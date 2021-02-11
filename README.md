# jenkins-in-k8s
Easy Jenkins Deploy in Kubernetes Cluster

Простой пример развёртывания Jenkins в кластере Kubernetes.
Компактный образ на Linux Alpine, быстрый и потребляющий минимум ресурсов.
1. Отредактируйте в манифесте pv.yml параметры доступа к NSF-шаре, в которой Jenkins будет хранить свои данные.
2. Создайте командой kubectl apply PervistentVolume, PersistentVolumeClaim, Deployment и Service.
3. Пользуйтесь ))
