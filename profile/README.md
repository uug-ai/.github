# Welcome to uug.ai

Cool, you are building vision models! But can you deploy 📦 and scale 🚀 them? You are not alone. Together with uug.ai, we scale machine learning models and computer vision algorithms to transform vision into innovative and impactful solutions, enriching lives and industries.

At uug.ai we are bringing machine learning for vision to life by implementing tools such as `kerberos.io` to scale a video network of ip cameras, applying MLOps best pratices to scale machine learning models through `kubernetes` and `docker` and making models interactive through custom user interfaces and industry specific use cases (e.g. `facial access control`). In the end a machine learning model with a UI, is just a model that nobody can use.

## Our products

### Kerberos.io

Kerberos.io comes with a range of solutions helping you to setup a small video surveillance deployment flawlessly, with just a few cameras, and scale out to a large enterprise deployment, with thousands of cameras. It provides features to bring your own cloud (on-premise, hybrid, cloud), bring your own storage (Ceph, Minio, GCP, AWS, Azure, Storj, etc) and bring your own cameras (RTSP H264 and H265). In other words, you run the show!

Each component in the Kerberos.io architecture can be installed how and where you want. This means you can create hybrid scenarios, or go for a full-cloud or full-onpremise deployment.

- [Kerberos Agent](https://github.com/kerberos-io/agent)
- [Kerberos Factory](https://github.com/kerberos-io/factory)
- [Kerberos Vault](https://github.com/kerberos-io/vault)
- [Kerberos Hub](https://github.com/kerberos-io/hub)

[![Prologue - How it works](https://github.com/kerberos-io/.github/blob/main/profile/Prologue%20-%20How%20it%20works.svg)](https://doc.kerberos.io/prologue/deployments/)

## Industry solutions

### Facial Access Control
We have build an open source product that relies on various face recognition models, and embedded it into a feature rich web application that allows an organisation to safely add and store biometric data and provide access to various tools and rooms through API's, IoT or IO devices. To deploy the model into a production environment, you might want to combine this with Kerberos.io to provide to scale.

[📚 Learn more about the project](https://github.com/uug-ai/facial-access-control)