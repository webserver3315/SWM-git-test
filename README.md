Github tutorial
Github tutorial2
3
HOTFIX!!!

1. iss53 브랜치 생성
2. 해당 브랜치에서 A 파일 수정 및 반영
3. MASTER 브랜치에서 HOTFIX 브랜치 생성
4. 해당 브랜치에서 B 파일 수정 및 반영
5. MASTER 브랜치에서 HOTFIX 브랜치를 MERGE해서 반영

1. iss53 브랜치에서 수정하던 파일을 한 번 더 수정하고 반영
2. master 브랜치에서 평행우주로 진행되고 있던 iss53 브랜치를 병합
이 때 merge commit
아까 hotfix: fastforward 이므로, 핫픽스는 merge할 때 별도의 commit이 발생하지 않음

1. 박살지구, 두배지구 브랜치 각각 생성
2. 박살지구 브랜치로 이동해 지구파일 박살상태로 정정
3. 두배지구 동일행동 수행
4. master 브랜치에서 박살지구 머지
5. master 브랜치에서 두배지구 머지 => 컨플릭트 발생
6. (상황조치) add 명령어를 통해 두배지구의 지구파일을 스테이지에 올리기
7. git merge --continue 명령을 통해 마무리
참고로, conflict 는 매우 흔하게 발생한다!!!


1. github에 저장소 생성
2. 해당 원격저장소를 로컬에 등록(git remote add)
3. git push -u origin master 를 통해 원격저장소에 현재 상황 반영
참고로, -u와 --set-upstream 이랑 같은 말이다!!!
4. 현재 로컬 master 브랜치에서 README 수정 후 commit
5. git push 를 통해 스토킹중인 저장소에 현재 브랜치의 상황을 반영

