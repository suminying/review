# OSS 내용 정리
##### 깃 설정 6가지                                                                                                           
$ git config --global user.name suminying - 사용자 이름                                                                       
$ git config --global user.email usm403@naver.com - 사용자 전자메일                                                          
$ git config --global core.autocrlf true - 줄바꿈 자동변환                                                                   
$ git config --global core.safecrlf false - 줄바꿈 안전 설정                                                                  
$ git config --global core.editor 'code --wait' - 기본 편집기 설정                                                            
$ git config --global init.defaultBranch main - 기본 브랜치 이름

##### 저장소 생성                                                                                                           
$ git init - 현재 티렉토리를 git repository로 만들기 위해서 사용                                                               
git init basic - 현재 폴더 하부에 폴더 basic을 생성하고 git repository로 만들기 위해서 사용

##### 커밋                                                                                                                  
$ git commit - 커밋 메시지를 입력할 기본 편집기 실행됨                                                                         
$ git commit -m 'message' - 커밋 메시지를 직접 입력                                                                            
$ git commit -a -m 'message' - 추가와 커밋을 함께 실행
##### 로그                                                                                                                  
$ git log 로그 이력 정보를 표시                                                                                               
$ git log --oneline - 로그 이력을 한 줄로 표시                                                                                 
$ git log [--patch|-p] - 로그 이력과 함께 파일의 변화

##### 파일 비교 diff                                                                                                        
$ git diff - 스테이징 영역 기준으로 작업 디렉토리 파일 비교                                                                    
$ git diff --staged HEAD - 깃 저장소 기준으로 스테이징 영역 파일 비교                                                           
$ git diff HEAD - 깃 저장소 기준으로 작업 디렉토리 파일 비교
git diff HEAD^HEAD - 커밋 간의 파일 비교                                                                                     
##### 파일 삭제 rm과 복원 restore
$ rm f - 디렉토리에서 파일 삭제                                                                                               
$ git rm f - 작업 디렉토리와 스테이징 영역에서 파일 삭제                                                                       
$ git rm --cached f - 스테이징 영역에서만 파일 삭제                                                                           
$ git restore f - 스테이징 영역의 상태를 작업 디렉토리에 복원                                                                  
$ git restore --staged f - 스테이징 영역에 복원                                                                              
$ git restore --source=HEAD --worktree f - 깃 저장소 상태를 작업 디렉토리에 복원                                               
$ git restore --source=HEAD --staged --worktree f - 깃 저장소 상태를 스테이징 영역과 작업 디렉토리에 함께 복원                  

##### 브랜치 개요와 관리                                                                                                    
$ git branch - 저장소 목록 보기                                                                                              
$ git



  


 
