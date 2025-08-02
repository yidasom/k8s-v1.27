# k8s-v1.27


## Kubernetes 설치용 Manifest 모음 : k8s-v1.27 용
- Calico (v3.26.4): pod 네트워크 플러그인
- Kubernetes Dashboard (v2.7.0): 클러스터 웹 UI
- Metrics Server (v0.6.3): Pod/Node 리소스 모니터링

### 사용법
```bash
kubectl apply -f calico.yaml
kubectl apply -f dashboard.yaml
kubectl apply -f metrics-server.yaml
```
