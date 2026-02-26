# infra-automation Repo

Ansible 기반 Kubernetes 초기 구성 자동화 레포지토리입니다.

<br>

## Structure

```
ansible/
 ├── inventory/
 │   └── hosts.ini
 ├── roles/
 │   ├── common-ssh/
 │   ├── k3s/
 │   └── argocd-install/
 └── site.yml
```

<br>

## Roles

* **common-ssh** : SSH 기본 설정
* **argocd-install** : ArgoCD 설치
* **k3s** : Kubernetes(k3s) 설치 (개인 실습 환경에서 사용)

<br>

## Design

* 클러스터 초기 구성 자동화
* 수동 설치 과정 제거
* Git 기반 인프라 이력 관리

