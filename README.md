# xai

류재석, 유경민, 최민혁 xai 기말 과제

* 리포트 작성 (https://jaeseokryu.notion.site/XAI_-Final-Exam-67da318a5aae483b86009edd04512083) </br>
  -Introduction [50% 작성] <br/>
  -Problem Formulation <br/>
  -Method <br/>
  -Experiments <br/>
  -Dicussion <br/>

* 참고 <br/>
[imagenet 1000 class 이름 및 번호](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a) <br/>
[gradcam 코드](https://github.com/jacobgil/pytorch-grad-cam)
[sample dataset from imagenet](https://www.kaggle.com/datasets/utkarshsaxenadn/animal-image-classification-dataset)

* kaggle에서 데이터셋을 받는 방법 <br/>
개인 kaggle token이 필요하고, 해당 json파일을 ~/.kaggle/ 에 두어야 한다. <br/>
`
! pip install -q kaggle <br/>
! mkdir ~/.kaggle <br/>
! cp kaggle.json ~/.kaggle/ <br/>
! chmod 600 ~/.kaggle/kaggle.json <br/>
! kaggle competitions download -c 'name-of-competition' 
`

* 할일
- [x] transformer에 gradCAM적용 (~11/20) <br/>
- [ ] 각자 xai기법 하나씩 적용해보기 (~11/24) <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [ ] attention flow (유경민) <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [ ] Integrated Gradients (최민혁) <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [ ] SHAP(Shapley Additive exPlanations)
(류재석) <br/>
- [0] 실험 설계 및 실험 진행 (~11/27) <br/>
- [ ] 기말 레포트 작성 (~12/3) <br/>
- [ ] 발표 ppt만들기 (~12/3) <br/>
