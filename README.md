# naver-blog-writer-codex

네이버 블로그 홈판(홈피드)·검색/AEO 글을 작성하고, 이미지 순차 생성·번호 지정·HTML 2종·태그·ZIP까지 만드는 에이전트 스킬입니다.

## 설치

Codex:

```bash
git clone https://github.com/ninestonelee/naver-blog-writer-codex.git ~/.codex/skills/naver-blog-writer-codex
```

Claude Code:

```bash
git clone https://github.com/ninestonelee/naver-blog-writer-codex.git ~/.claude/skills/naver-blog-writer-codex
```

## 사용 예

- `이 기사로 홈판용 블로그 글 써줘`
- `에어컨 청소 비용 검색형 글로 정리해줘`
- `해시태그 한 줄로 줘`

자세한 규칙은 [SKILL.md](SKILL.md)와 `references/` 폴더를 참고하세요.

## 주의

- 생성된 글은 사람이 검토한 뒤 직접 발행합니다. 자동 발행은 포함하지 않습니다.
- `references/legal_check.md`의 법령·판례 정보는 참고용이며 법률 검증을 거친 내용이 아닙니다.
