# Mermaid diagrams of the generalisations
## care activities bundle
```mermaid
classDiagram
    direction BT
    class f7c3ea77-77bc-403e-a234-d8853f947f40 ["care activities bundle"]
    
    class 7087a642-bce6-4afa-b543-619a7ee8a1b0 ["needed care activity"]
    
    7087a642-bce6-4afa-b543-619a7ee8a1b0 --|> f7c3ea77-77bc-403e-a234-d8853f947f40

```
## care activity
```mermaid
classDiagram
    direction BT
    class 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d ["care activity"]
    
    class dc07fff5-a43b-4864-b6e0-09c653fe0385 ["adverse event management"]
    
    class fd2c26ed-422f-41e1-aab0-0192d550e443 ["care activity management"]
    
    class 09eb0a5d-e7e0-4888-8f2b-815bf3217441 ["care assessment"]
    
    class b9488049-fb10-46ff-9eb9-bd6ad482ec76 ["care needs assessment"]
    
    class d58d7cfd-6f75-4a35-a858-7ac8a31b71b6 ["health condition assessment"]
    
    class 1453dfd5-bac0-48ba-a3d7-02c0a4b47b50 ["care communication"]
    
    class c00fde7b-fd40-4b8a-9a33-c68501ac2e97 ["care documenting"]
    
    class 8c73e77f-5318-4136-b648-3a6164c96458 ["care evaluation"]
    
    class cdbed706-d908-4659-a8ef-6337d54cdac3 ["care process evaluation"]
    
    class d0b62045-00cd-4d13-b27f-36963ea9d6c2 ["care investigation"]
    
    class d7644066-60da-4da8-9035-58238dd23ee0 ["care planning"]
    
    class b4841bcb-0012-4f01-946e-5e1af6956084 ["care provider activity"]
    
    class ac79b332-ded2-4731-98f0-689cced14673 ["social care provider activity"]
    
    class 7e3c529e-a5fc-40b1-a146-efe047e977f8 ["care third party activity"]
    
    class fc8830d4-e9d7-4f72-b3b6-8dfd72ef7890 ["prescribed third party activity"]
    
    class 4f4885e7-bb69-4a2b-85e6-e04270dac9fe ["care treatment"]
    
    class 38ab9ebf-413d-4d08-a41f-a449e9755c60 ["self-care"]
    
    class 5ceb4260-3cb2-4e18-8fc9-fd33ea1d61a1 ["prescribed self-care"]
    
    dc07fff5-a43b-4864-b6e0-09c653fe0385 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    fd2c26ed-422f-41e1-aab0-0192d550e443 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    09eb0a5d-e7e0-4888-8f2b-815bf3217441 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    1453dfd5-bac0-48ba-a3d7-02c0a4b47b50 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    c00fde7b-fd40-4b8a-9a33-c68501ac2e97 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    8c73e77f-5318-4136-b648-3a6164c96458 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    d0b62045-00cd-4d13-b27f-36963ea9d6c2 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    b9488049-fb10-46ff-9eb9-bd6ad482ec76 --|> 09eb0a5d-e7e0-4888-8f2b-815bf3217441
    d7644066-60da-4da8-9035-58238dd23ee0 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    cdbed706-d908-4659-a8ef-6337d54cdac3 --|> 8c73e77f-5318-4136-b648-3a6164c96458
    b4841bcb-0012-4f01-946e-5e1af6956084 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    7e3c529e-a5fc-40b1-a146-efe047e977f8 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    4f4885e7-bb69-4a2b-85e6-e04270dac9fe --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    d58d7cfd-6f75-4a35-a858-7ac8a31b71b6 --|> 09eb0a5d-e7e0-4888-8f2b-815bf3217441
    5ceb4260-3cb2-4e18-8fc9-fd33ea1d61a1 --|> 38ab9ebf-413d-4d08-a41f-a449e9755c60
    fc8830d4-e9d7-4f72-b3b6-8dfd72ef7890 --|> 7e3c529e-a5fc-40b1-a146-efe047e977f8
    38ab9ebf-413d-4d08-a41f-a449e9755c60 --|> 9db96600-9f5a-4eed-b7e0-a2fa180bdd9d
    ac79b332-ded2-4731-98f0-689cced14673 --|> b4841bcb-0012-4f01-946e-5e1af6956084

```
## care actor
```mermaid
classDiagram
    direction BT
    class b40f06bf-cff4-4b6a-a07e-422c6929e50a ["care actor"]
    
    class 06aff740-4b76-407d-b907-2a2378203748 ["care personnel"]
    
    class 6e2f91b1-d262-4aad-8de4-f07dc6ddcb99 ["care professional"]
    
    class 35ad7fb0-4f44-4f94-8508-cd69dd0632c2 ["care provider"]
    
    class ae58349c-941a-420a-a880-7162fb4e90b9 ["care organization"]
    
    class 6cdf58a5-986d-492c-96df-717a4d7daf91 ["care third party"]
    
    class 112d2d96-f09f-4c7b-beae-91f1f1f9abf7 ["care supporting organization"]
    
    class 537621a0-e4e5-4bec-9b48-5542f9db43e5 ["other carer"]
    
    class 86fec362-02dc-4b26-85f3-e1c3243c1c09 ["subject of care proxy"]
    
    class a41a1596-fa3c-4c2b-aa3a-a69119a2a5de ["subject of care"]
    
    ae58349c-941a-420a-a880-7162fb4e90b9 --|> 35ad7fb0-4f44-4f94-8508-cd69dd0632c2
    06aff740-4b76-407d-b907-2a2378203748 --|> 35ad7fb0-4f44-4f94-8508-cd69dd0632c2
    06aff740-4b76-407d-b907-2a2378203748 --|> b40f06bf-cff4-4b6a-a07e-422c6929e50a
    6e2f91b1-d262-4aad-8de4-f07dc6ddcb99 --|> 06aff740-4b76-407d-b907-2a2378203748
    35ad7fb0-4f44-4f94-8508-cd69dd0632c2 --|> b40f06bf-cff4-4b6a-a07e-422c6929e50a
    112d2d96-f09f-4c7b-beae-91f1f1f9abf7 --|> 6cdf58a5-986d-492c-96df-717a4d7daf91
    6cdf58a5-986d-492c-96df-717a4d7daf91 --|> b40f06bf-cff4-4b6a-a07e-422c6929e50a
    537621a0-e4e5-4bec-9b48-5542f9db43e5 --|> 6cdf58a5-986d-492c-96df-717a4d7daf91
    a41a1596-fa3c-4c2b-aa3a-a69119a2a5de --|> b40f06bf-cff4-4b6a-a07e-422c6929e50a
    86fec362-02dc-4b26-85f3-e1c3243c1c09 --|> 6cdf58a5-986d-492c-96df-717a4d7daf91

```
## care contact
```mermaid
classDiagram
    direction BT
    class 067b6a61-761f-4227-97fe-0b83a4088b6d ["care contact"]
    
    class d4482e7d-9caa-447c-843e-0ad469283fdd ["initial contact"]
    
    d4482e7d-9caa-447c-843e-0ad469283fdd --|> 067b6a61-761f-4227-97fe-0b83a4088b6d

```
## care plan
```mermaid
classDiagram
    direction BT
    class 3a36d00e-d3f4-499b-b1f6-11b461697c1d ["care plan"]
    
    class d8f95456-5163-4d07-be21-2937a283b730 ["clinical care plan"]
    
    class 065e4066-2655-41fd-ab75-cdebefc6438e ["integrated care plan"]
    
    class 7343c179-5f19-43c3-8d96-dbc8721ee937 ["social care plan"]
    
    d8f95456-5163-4d07-be21-2937a283b730 --|> 3a36d00e-d3f4-499b-b1f6-11b461697c1d
    065e4066-2655-41fd-ab75-cdebefc6438e --|> 3a36d00e-d3f4-499b-b1f6-11b461697c1d
    7343c179-5f19-43c3-8d96-dbc8721ee937 --|> 3a36d00e-d3f4-499b-b1f6-11b461697c1d

```
## care process
```mermaid
classDiagram
    direction BT
    class aba83851-1d98-4834-a505-5b6a242f6196 ["care process"]
    
    class 85e33cbb-082b-465c-a759-fd823e8843b9 ["continuity of care process"]
    
    85e33cbb-082b-465c-a759-fd823e8843b9 --|> aba83851-1d98-4834-a505-5b6a242f6196

```
## data
```mermaid
classDiagram
    direction BT
    class a4d70b96-866c-4b00-aac1-b6f97bf553bf ["data"]
    
    class 7ad6ad2a-5670-48ad-9d7f-837f5b175cef ["care data"]
    
    7ad6ad2a-5670-48ad-9d7f-837f5b175cef --|> a4d70b96-866c-4b00-aac1-b6f97bf553bf

```
## event
```mermaid
classDiagram
    direction BT
    class 4fb8d6e6-9dbe-4216-8230-db34618e9052 ["event"]
    
    class 9e661cb5-c2d2-4981-97d8-581ea3617964 ["unintended event"]
    
    class 95c4fd99-6150-4fe9-883c-bd5a776d52ee ["adverse event"]
    
    95c4fd99-6150-4fe9-883c-bd5a776d52ee --|> 9e661cb5-c2d2-4981-97d8-581ea3617964
    9e661cb5-c2d2-4981-97d8-581ea3617964 --|> 4fb8d6e6-9dbe-4216-8230-db34618e9052

```
## health condition
```mermaid
classDiagram
    direction BT
    class c7d287a0-fb7e-40aa-9893-d75944a15925 ["health condition"]
    
    class 7c9ffd22-c613-4047-b4f8-3ff7944cb48a ["health issue"]
    
    class 3b009b93-19aa-414b-bff4-a40feb00f77e ["clinical issue"]
    
    class 77cc8828-fd90-41e2-bf6c-369878198ae4 ["health problem"]
    
    class ff173938-c30a-4dbd-8be4-5fed17c34e24 ["social issue"]
    
    class 2740e08e-94fe-4294-9400-985a7b65b25a ["observed condition"]
    
    class b8e873a7-5a71-4597-b10e-b114c06cec1d ["professionally assessed condition"]
    
    class 36b9a142-6aaa-4bf7-a0b5-eb9831d8ffd7 ["vulnerability"]
    
    class ef2eea9f-9ff3-4802-bfaa-7f0b5372ed45 ["working diagnosis"]
    
    class 8d856f66-a8ae-4dbb-a150-158b6faab86e ["potential health condition"]
    
    class f700be81-176c-46c6-a704-bbb248197e44 ["considered condition"]
    
    class a3b8eda7-d76f-4262-afcb-4e1a94660c6e ["excluded condition"]
    
    class 4e4f1f57-b731-4a0f-8d45-fa35d8d1fce1 ["prognostic condition"]
    
    class 47ca592b-2b1f-4c1e-b733-a624a35d4f22 ["risk condition"]
    
    class a0316e9b-0f53-4bdf-8f3d-6eb6fa4bbee7 ["target condition"]
    
    class 83b5b032-8ac3-4727-9a8f-4b9f7b21ff68 ["resultant condition"]
    
    3b009b93-19aa-414b-bff4-a40feb00f77e --|> 7c9ffd22-c613-4047-b4f8-3ff7944cb48a
    f700be81-176c-46c6-a704-bbb248197e44 --|> 8d856f66-a8ae-4dbb-a150-158b6faab86e
    a3b8eda7-d76f-4262-afcb-4e1a94660c6e --|> f700be81-176c-46c6-a704-bbb248197e44
    7c9ffd22-c613-4047-b4f8-3ff7944cb48a --|> c7d287a0-fb7e-40aa-9893-d75944a15925
    77cc8828-fd90-41e2-bf6c-369878198ae4 --|> 7c9ffd22-c613-4047-b4f8-3ff7944cb48a
    2740e08e-94fe-4294-9400-985a7b65b25a --|> c7d287a0-fb7e-40aa-9893-d75944a15925
    8d856f66-a8ae-4dbb-a150-158b6faab86e --|> c7d287a0-fb7e-40aa-9893-d75944a15925
    b8e873a7-5a71-4597-b10e-b114c06cec1d --|> 2740e08e-94fe-4294-9400-985a7b65b25a
    b8e873a7-5a71-4597-b10e-b114c06cec1d --|> f700be81-176c-46c6-a704-bbb248197e44
    4e4f1f57-b731-4a0f-8d45-fa35d8d1fce1 --|> 8d856f66-a8ae-4dbb-a150-158b6faab86e
    83b5b032-8ac3-4727-9a8f-4b9f7b21ff68 --|> c7d287a0-fb7e-40aa-9893-d75944a15925
    47ca592b-2b1f-4c1e-b733-a624a35d4f22 --|> 8d856f66-a8ae-4dbb-a150-158b6faab86e
    ff173938-c30a-4dbd-8be4-5fed17c34e24 --|> 7c9ffd22-c613-4047-b4f8-3ff7944cb48a
    a0316e9b-0f53-4bdf-8f3d-6eb6fa4bbee7 --|> 8d856f66-a8ae-4dbb-a150-158b6faab86e
    36b9a142-6aaa-4bf7-a0b5-eb9831d8ffd7 --|> b8e873a7-5a71-4597-b10e-b114c06cec1d
    ef2eea9f-9ff3-4802-bfaa-7f0b5372ed45 --|> b8e873a7-5a71-4597-b10e-b114c06cec1d

```
## health condition period
```mermaid
classDiagram
    direction BT
    class fb9badce-a5b0-4364-91d2-baac708af7b3 ["health condition period"]
    
    class 91bfe09c-b8a5-4e5f-b2e7-1789e979544b ["health condition delay"]
    
    91bfe09c-b8a5-4e5f-b2e7-1789e979544b --|> fb9badce-a5b0-4364-91d2-baac708af7b3

```
## health need
```mermaid
classDiagram
    direction BT
    class 63183c6f-89fb-4f4d-8baf-c91933afde12 ["health need"]
    
    class dd48858e-ef50-400e-a2d1-3dd44764d3d4 ["social need"]
    
    dd48858e-ef50-400e-a2d1-3dd44764d3d4 --|> 63183c6f-89fb-4f4d-8baf-c91933afde12

```
## health record extract
```mermaid
classDiagram
    direction BT
    class 094a2bf2-4a84-4dcc-8d99-51324cb57791 ["health record extract"]
    
    class 65e0cf86-ea28-4273-a3c1-e455ee906445 ["electronic health record extract"]
    
    class 19ac40c1-6710-4439-ada5-ee5fc3e6b3ab ["health summary"]
    
    class 2ef348d2-dcbf-4f41-96b5-469819a2f210 ["health concern"]
    
    class e3d50d4a-6367-42f1-96e3-55be23436e17 ["health report"]
    
    class 09c5fa74-d233-40ee-b2f2-389919d9311f ["discharge report"]
    
    class 3438e46e-d41b-4501-a68e-23ffaf16ed00 ["discharge summary"]
    
    class 454aff3d-2dac-423f-a7a3-7f51419c6633 ["health certificate"]
    
    class 0a4abd91-9a9d-4690-b020-1908fbc86327 ["social care report"]
    
    class eefdc4e5-1f04-4d38-baea-bfc6cefb9d08 ["social record extract"]
    
    09c5fa74-d233-40ee-b2f2-389919d9311f --|> e3d50d4a-6367-42f1-96e3-55be23436e17
    3438e46e-d41b-4501-a68e-23ffaf16ed00 --|> 09c5fa74-d233-40ee-b2f2-389919d9311f
    65e0cf86-ea28-4273-a3c1-e455ee906445 --|> 094a2bf2-4a84-4dcc-8d99-51324cb57791
    454aff3d-2dac-423f-a7a3-7f51419c6633 --|> e3d50d4a-6367-42f1-96e3-55be23436e17
    2ef348d2-dcbf-4f41-96b5-469819a2f210 --|> 094a2bf2-4a84-4dcc-8d99-51324cb57791
    e3d50d4a-6367-42f1-96e3-55be23436e17 --|> 094a2bf2-4a84-4dcc-8d99-51324cb57791
    19ac40c1-6710-4439-ada5-ee5fc3e6b3ab --|> 65e0cf86-ea28-4273-a3c1-e455ee906445
    19ac40c1-6710-4439-ada5-ee5fc3e6b3ab --|> 094a2bf2-4a84-4dcc-8d99-51324cb57791
    0a4abd91-9a9d-4690-b020-1908fbc86327 --|> e3d50d4a-6367-42f1-96e3-55be23436e17
    eefdc4e5-1f04-4d38-baea-bfc6cefb9d08 --|> 094a2bf2-4a84-4dcc-8d99-51324cb57791

```
## health related period
```mermaid
classDiagram
    direction BT
    class de7ec2b2-e96c-43b8-839c-d511f32bcc0e ["health related period"]
    
    class e946367a-cbe7-492e-9759-f2eed680dae4 ["care activity delay"]
    
    class 91bfe09c-b8a5-4e5f-b2e7-1789e979544b ["health condition delay"]
    
    class a4eea000-cd03-49da-bac7-7923b7dcb3cb ["resource delay"]
    
    class 10f193a8-a98b-48f0-af81-959e63c48862 ["subject of care preference delay"]
    
    class 1a01bcf8-b6ca-4a2b-ac68-116da890b10a ["care activity period"]
    
    class 793a6366-fd5f-4acd-b314-2537a3122c75 ["contact period"]
    
    class db0b390f-48e4-4393-8b1c-03c4e07807c6 ["indirect care activity period"]
    
    class a7e86db3-aead-45ff-ada2-10b2f677755b ["prescribed self-care period"]
    
    class 9b0aa9dd-1ab1-428d-8d39-62a046f77be2 ["episode of care"]
    
    class cd61b9e3-64bd-4986-9656-74abfac74a3c ["health approach"]
    
    class ac4f39db-12c6-4473-a91f-b1cc130f8d6c ["mandated period of care"]
    
    e946367a-cbe7-492e-9759-f2eed680dae4 --|> de7ec2b2-e96c-43b8-839c-d511f32bcc0e
    1a01bcf8-b6ca-4a2b-ac68-116da890b10a --|> de7ec2b2-e96c-43b8-839c-d511f32bcc0e
    793a6366-fd5f-4acd-b314-2537a3122c75 --|> 1a01bcf8-b6ca-4a2b-ac68-116da890b10a
    9b0aa9dd-1ab1-428d-8d39-62a046f77be2 --|> de7ec2b2-e96c-43b8-839c-d511f32bcc0e
    cd61b9e3-64bd-4986-9656-74abfac74a3c --|> 9b0aa9dd-1ab1-428d-8d39-62a046f77be2
    91bfe09c-b8a5-4e5f-b2e7-1789e979544b --|> e946367a-cbe7-492e-9759-f2eed680dae4
    db0b390f-48e4-4393-8b1c-03c4e07807c6 --|> 1a01bcf8-b6ca-4a2b-ac68-116da890b10a
    ac4f39db-12c6-4473-a91f-b1cc130f8d6c --|> de7ec2b2-e96c-43b8-839c-d511f32bcc0e
    a7e86db3-aead-45ff-ada2-10b2f677755b --|> 1a01bcf8-b6ca-4a2b-ac68-116da890b10a
    a4eea000-cd03-49da-bac7-7923b7dcb3cb --|> e946367a-cbe7-492e-9759-f2eed680dae4
    10f193a8-a98b-48f0-af81-959e63c48862 --|> e946367a-cbe7-492e-9759-f2eed680dae4

```
## health state
```mermaid
classDiagram
    direction BT
    class 8dcfa7b1-75be-4297-bb6f-6aad0335f01d ["health state"]
    
    class a9954d0f-3f32-4a6f-b54f-4840359b16bb ["input health state"]
    
    class 85a91499-8759-401d-a757-3ee66b0d7910 ["output health state"]
    
    a9954d0f-3f32-4a6f-b54f-4840359b16bb --|> 8dcfa7b1-75be-4297-bb6f-6aad0335f01d
    85a91499-8759-401d-a757-3ee66b0d7910 --|> 8dcfa7b1-75be-4297-bb6f-6aad0335f01d

```
## health thread
```mermaid
classDiagram
    direction BT
    class 3ed9937d-d711-4b45-8e2f-24aff2fbb98e ["health thread"]
    
    class 653143ec-e071-446b-a373-de0107056c4e ["health problem list"]
    
    653143ec-e071-446b-a373-de0107056c4e --|> 3ed9937d-d711-4b45-8e2f-24aff2fbb98e

```
## information
```mermaid
classDiagram
    direction BT
    class afd4fd52-d30a-494f-bacb-1535ec193f1f ["information"]
    
    class 0e8398d8-c793-4a48-9d0b-6f62f67e1dc4 ["care information"]
    
    class d5a711a8-d0e7-4684-875f-cceb05ecefef ["care information for import"]
    
    class f256eb01-873d-48f2-b078-c6553f37fb69 ["non-ratified care information"]
    
    class 3f846645-894e-4d9b-b730-373705caebf4 ["health record component"]
    
    class 89c4f328-13d6-4f4d-acc9-a9ed07a2c3c2 ["COMPOSITION"]
    
    class 8df99cae-ca37-43d6-a9ac-d5e15be72a12 ["ENTRY"]
    
    class 6cbd9db6-f009-4071-ab3c-72cf446a5f09 ["FOLDER"]
    
    class ede4cc48-c085-47bf-81fb-e8fda54daea0 ["ITEM"]
    
    class 566e7943-0676-4fe3-a0a8-59f5864418db ["CLUSTER"]
    
    class 3674ba1d-3427-479e-aacd-5a7e5bd9c899 ["ELEMENT"]
    
    class d0203ff8-35d4-40c5-b393-96a7293f18b8 ["SECTION"]
    
    0e8398d8-c793-4a48-9d0b-6f62f67e1dc4 --|> afd4fd52-d30a-494f-bacb-1535ec193f1f
    d5a711a8-d0e7-4684-875f-cceb05ecefef --|> 0e8398d8-c793-4a48-9d0b-6f62f67e1dc4
    566e7943-0676-4fe3-a0a8-59f5864418db --|> ede4cc48-c085-47bf-81fb-e8fda54daea0
    89c4f328-13d6-4f4d-acc9-a9ed07a2c3c2 --|> 3f846645-894e-4d9b-b730-373705caebf4
    3674ba1d-3427-479e-aacd-5a7e5bd9c899 --|> ede4cc48-c085-47bf-81fb-e8fda54daea0
    8df99cae-ca37-43d6-a9ac-d5e15be72a12 --|> 3f846645-894e-4d9b-b730-373705caebf4
    6cbd9db6-f009-4071-ab3c-72cf446a5f09 --|> 3f846645-894e-4d9b-b730-373705caebf4
    3f846645-894e-4d9b-b730-373705caebf4 --|> afd4fd52-d30a-494f-bacb-1535ec193f1f
    ede4cc48-c085-47bf-81fb-e8fda54daea0 --|> 3f846645-894e-4d9b-b730-373705caebf4
    f256eb01-873d-48f2-b078-c6553f37fb69 --|> 0e8398d8-c793-4a48-9d0b-6f62f67e1dc4
    d0203ff8-35d4-40c5-b393-96a7293f18b8 --|> 3f846645-894e-4d9b-b730-373705caebf4

```
## knowledge
```mermaid
classDiagram
    direction BT
    class 0a17809e-be0d-4637-8a2f-0aae4d4bb7da ["knowledge"]
    
    class 665a81e6-8241-4d63-84e0-bbfb1001c51d ["care guideline"]
    
    class 178d5c51-1272-4886-9422-cb75c3ad42cd ["protocol"]
    
    class 2c3fed77-736b-402c-9d7f-f085cd3d0174 ["care pathway"]
    
    class 3f087280-d538-4c73-a743-5c94196371f9 ["core care plan"]
    
    class fc82bf4b-676c-4ae3-b166-359d54a7236a ["information model"]
    
    665a81e6-8241-4d63-84e0-bbfb1001c51d --|> 0a17809e-be0d-4637-8a2f-0aae4d4bb7da
    2c3fed77-736b-402c-9d7f-f085cd3d0174 --|> 0a17809e-be0d-4637-8a2f-0aae4d4bb7da
    3f087280-d538-4c73-a743-5c94196371f9 --|> 0a17809e-be0d-4637-8a2f-0aae4d4bb7da
    fc82bf4b-676c-4ae3-b166-359d54a7236a --|> 0a17809e-be0d-4637-8a2f-0aae4d4bb7da
    178d5c51-1272-4886-9422-cb75c3ad42cd --|> 665a81e6-8241-4d63-84e0-bbfb1001c51d

```
## mandate
```mermaid
classDiagram
    direction BT
    class d9484351-8f6a-4cab-ad92-b844eee8ccd2 ["mandate"]
    
    class 820f67b6-f718-4c09-a097-6d16be2a5b16 ["care employment"]
    
    class d124a289-7465-4e25-8672-fec02119fb9d ["care mandate"]
    
    class bd9ee1b7-b197-4027-92eb-8294df1bd262 ["care activity mandate"]
    
    class 1b6e3a68-57fe-452b-918b-041a204b3399 ["care period mandate"]
    
    class 8b81cc8c-acce-4ef1-942e-81583c336afc ["continuity facilitator mandate"]
    
    class 89f28968-af6f-41e4-b5f4-9f375d03a9ba ["mandate to export personal information"]
    
    class b8aa75c1-a052-4ad9-a844-315adfd47363 ["request mandate"]
    
    class ab80dbac-8522-45f7-853a-7905bd1c91d4 ["care professional entitlement"]
    
    class 7c83aba3-84cb-41ac-8245-e2e0734471fb ["clinical care activity mandate"]
    
    class 0aa436bf-12ec-4611-afad-78dfde13d17f ["proxy mandate"]
    
    class 100cc991-af33-442d-8d4a-589418a23ede ["social care activity mandate"]
    
    class 86fec362-02dc-4b26-85f3-e1c3243c1c09 ["subject of care proxy"]
    
    bd9ee1b7-b197-4027-92eb-8294df1bd262 --|> d124a289-7465-4e25-8672-fec02119fb9d
    820f67b6-f718-4c09-a097-6d16be2a5b16 --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    d124a289-7465-4e25-8672-fec02119fb9d --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    1b6e3a68-57fe-452b-918b-041a204b3399 --|> d124a289-7465-4e25-8672-fec02119fb9d
    ab80dbac-8522-45f7-853a-7905bd1c91d4 --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    7c83aba3-84cb-41ac-8245-e2e0734471fb --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    8b81cc8c-acce-4ef1-942e-81583c336afc --|> d124a289-7465-4e25-8672-fec02119fb9d
    89f28968-af6f-41e4-b5f4-9f375d03a9ba --|> d124a289-7465-4e25-8672-fec02119fb9d
    0aa436bf-12ec-4611-afad-78dfde13d17f --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    b8aa75c1-a052-4ad9-a844-315adfd47363 --|> d124a289-7465-4e25-8672-fec02119fb9d
    100cc991-af33-442d-8d4a-589418a23ede --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2
    86fec362-02dc-4b26-85f3-e1c3243c1c09 --|> d9484351-8f6a-4cab-ad92-b844eee8ccd2

```
## request for care
```mermaid
classDiagram
    direction BT
    class 161d6d94-732e-4524-9b7d-ad2abb6f740d ["request for care"]
    
    class c7be98e2-1e86-4ddb-a301-3f4548137194 ["initial request for care"]
    
    class 8f6f8e0a-f9e7-49d5-998b-44706ed199f4 ["referral"]
    
    class d54dd9e1-f8bb-4b5f-be6b-75d7a0fdb788 ["request for service"]
    
    class 7f93f2e8-34ed-41cf-9c6f-6140356b6621 ["care information request"]
    
    7f93f2e8-34ed-41cf-9c6f-6140356b6621 --|> d54dd9e1-f8bb-4b5f-be6b-75d7a0fdb788
    c7be98e2-1e86-4ddb-a301-3f4548137194 --|> 161d6d94-732e-4524-9b7d-ad2abb6f740d
    8f6f8e0a-f9e7-49d5-998b-44706ed199f4 --|> 161d6d94-732e-4524-9b7d-ad2abb6f740d
    d54dd9e1-f8bb-4b5f-be6b-75d7a0fdb788 --|> 161d6d94-732e-4524-9b7d-ad2abb6f740d

```
## resource
```mermaid
classDiagram
    direction BT
    class 72e2d618-17f5-41eb-ad97-39726338fccc ["resource"]
    
    class 2c026a2e-4093-4a99-bf3b-3c9a9738e57c ["care funds"]
    
    class ead47509-543a-4e1d-b17f-3d3e9c8fb3a5 ["care resource"]
    
    class 06aff740-4b76-407d-b907-2a2378203748 ["care personnel"]
    
    class 6e2f91b1-d262-4aad-8de4-f07dc6ddcb99 ["care professional"]
    
    class db944af3-770b-4627-b13d-43be515ca6f6 ["care service directory"]
    
    class 4b9364b4-dbac-42dc-b8fe-264f1012135a ["medical device"]
    
    class 5aeac937-b067-4148-9343-9c70d46b9fcb ["automatic medical device"]
    
    class c61ac522-1e38-4c08-a987-7e8e4d8fb987 ["medicinal product"]
    
    class f85fcb65-955a-4fae-a3ca-e9699df0066f ["point of care"]
    
    class c54beb09-8e2e-4871-a3fe-19959b94f7e4 ["data repository"]
    
    class c278ce53-b11b-4926-9722-3fb680da75aa ["health record"]
    
    class 702907af-f44c-4a99-8f4e-cba0475abd13 ["electronic health record"]
    
    class 313dbdc6-aeb0-4519-9027-ce5bc8002aec ["personal health record"]
    
    class b6cf0d3a-561d-4163-89b3-8df519bb8aff ["professional health record"]
    
    class 7b47f4fa-bf30-4e6f-8ccf-07fc8e056062 ["sharable data repository"]
    
    class 62cf6cea-277a-48f1-aa8e-850372273836 ["summarized care information repository"]
    
    5aeac937-b067-4148-9343-9c70d46b9fcb --|> 4b9364b4-dbac-42dc-b8fe-264f1012135a
    2c026a2e-4093-4a99-bf3b-3c9a9738e57c --|> 72e2d618-17f5-41eb-ad97-39726338fccc
    06aff740-4b76-407d-b907-2a2378203748 --|> ead47509-543a-4e1d-b17f-3d3e9c8fb3a5
    6e2f91b1-d262-4aad-8de4-f07dc6ddcb99 --|> 06aff740-4b76-407d-b907-2a2378203748
    ead47509-543a-4e1d-b17f-3d3e9c8fb3a5 --|> 72e2d618-17f5-41eb-ad97-39726338fccc
    db944af3-770b-4627-b13d-43be515ca6f6 --|> ead47509-543a-4e1d-b17f-3d3e9c8fb3a5
    c54beb09-8e2e-4871-a3fe-19959b94f7e4 --|> 72e2d618-17f5-41eb-ad97-39726338fccc
    702907af-f44c-4a99-8f4e-cba0475abd13 --|> c278ce53-b11b-4926-9722-3fb680da75aa
    c278ce53-b11b-4926-9722-3fb680da75aa --|> c54beb09-8e2e-4871-a3fe-19959b94f7e4
    4b9364b4-dbac-42dc-b8fe-264f1012135a --|> ead47509-543a-4e1d-b17f-3d3e9c8fb3a5
    c61ac522-1e38-4c08-a987-7e8e4d8fb987 --|> ead47509-543a-4e1d-b17f-3d3e9c8fb3a5
    313dbdc6-aeb0-4519-9027-ce5bc8002aec --|> c278ce53-b11b-4926-9722-3fb680da75aa
    f85fcb65-955a-4fae-a3ca-e9699df0066f --|> ead47509-543a-4e1d-b17f-3d3e9c8fb3a5
    b6cf0d3a-561d-4163-89b3-8df519bb8aff --|> c278ce53-b11b-4926-9722-3fb680da75aa
    7b47f4fa-bf30-4e6f-8ccf-07fc8e056062 --|> c54beb09-8e2e-4871-a3fe-19959b94f7e4
    62cf6cea-277a-48f1-aa8e-850372273836 --|> 7b47f4fa-bf30-4e6f-8ccf-07fc8e056062

```
## role
```mermaid
classDiagram
    direction BT
    class faae5d89-dbed-4ce7-8312-cf44671ef8a9 ["role"]
    
    class f9f68904-81d6-4f42-9efe-41843fd1f3de ["organization role"]
    
    class 4b2f4ba0-8161-4732-a806-bbeaccb1661b ["person role"]
    
    class e1853a99-c0c0-4810-801a-e5f38238b077 ["care performer"]
    
    class 78071a9f-369a-4901-ac44-654558c9729e ["prescriber"]
    
    class 537621a0-e4e5-4bec-9b48-5542f9db43e5 ["other carer"]
    
    class 1454e668-dc11-43f0-97e7-2eae11bd40a2 ["self-care performer"]
    
    class a41a1596-fa3c-4c2b-aa3a-a69119a2a5de ["subject of care"]
    
    class 3e4137ce-d8f3-403b-bff2-78515aa7d6d0 ["third party care performer"]
    
    e1853a99-c0c0-4810-801a-e5f38238b077 --|> 4b2f4ba0-8161-4732-a806-bbeaccb1661b
    f9f68904-81d6-4f42-9efe-41843fd1f3de --|> faae5d89-dbed-4ce7-8312-cf44671ef8a9
    537621a0-e4e5-4bec-9b48-5542f9db43e5 --|> 4b2f4ba0-8161-4732-a806-bbeaccb1661b
    4b2f4ba0-8161-4732-a806-bbeaccb1661b --|> faae5d89-dbed-4ce7-8312-cf44671ef8a9
    78071a9f-369a-4901-ac44-654558c9729e --|> e1853a99-c0c0-4810-801a-e5f38238b077
    1454e668-dc11-43f0-97e7-2eae11bd40a2 --|> 4b2f4ba0-8161-4732-a806-bbeaccb1661b
    a41a1596-fa3c-4c2b-aa3a-a69119a2a5de --|> 4b2f4ba0-8161-4732-a806-bbeaccb1661b
    3e4137ce-d8f3-403b-bff2-78515aa7d6d0 --|> 4b2f4ba0-8161-4732-a806-bbeaccb1661b

```
## subject of care desire
```mermaid
classDiagram
    direction BT
    class 174db6b0-8561-4c33-a5f6-18d0eee999d2 ["subject of care desire"]
    
    class 92b51f00-0b80-4169-98e8-148e43bd9bdc ["objection"]
    
    92b51f00-0b80-4169-98e8-148e43bd9bdc --|> 174db6b0-8561-4c33-a5f6-18d0eee999d2

```
