selenium, bs4 를 사용해 youtube 검색해 관련 동영상 정보와 각 영상별 댓글을 크롤링한다.
검색 기준은 해시태그를 사용한 '#검색어' 로 한다.
필터는 동영상만 보이기, 관련성 높은 순으로 읽어온다.
가져오는 정보는 채널관련정보 - 유튜브명, 채널 URL, 아바타 이미지, 구독자 수, 
영상관련정보 - 제목, 업로드 일자, 영상 재생횟수, 썸네일 이미지, 좋아요/싫어요 갯수, 댓글
이후 댓글들의 긍/부정 여부를 판별하기 위해 제목이 영문+기호 등으로 구성된 URL만 사용하고, 댓글은 영문만 사용한다.
