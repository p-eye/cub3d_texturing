# cub3d_texturing
Description of cub3D texturing

----

cub3d 과제를 진행하면서 <br /> <br />
* [taelee님의 mlx 예제](https://github.com/taelee42/mlx_example) <br />
* [로데브 레이캐스팅 튜토리얼](https://lodev.org/cgtutor/raycasting.html) <br />
* [mihykim님의 로데브 번역본](https://github.com/365kim/raycasting_tutorial) <br />
* [yohlee님의 로데브 C 버전](https://github.com/l-yohai/cub3d) <br /> <br />

자료들로부터 많은 도움을 받았습니다.
<br /><br />
이 글도 위 자료들을 바탕으로 작성했기 때문에 참고하시면 좋을 것 같습니다.

<br /><br />
이 글엔 제가 cub3d 진행 중 '텍스쳐 처리'를 학습한 과정이 정리되어 있습니다. <br />

따라서 로데브 튜토리얼 중 아래 부분만 담겨 있습니다. <br />

* 벽에 텍스쳐 넣기 - 로데브 said, "affine texture mapping" (subejct mandatory)
* 천장, 바닥에 텍스쳐 넣기 - 로데브 said, "scanline by scanline" (subject bonus)
* 텍스쳐에 투명도 넣기 (extra)

그리고 이해를 돕기 위해 첫 페이지에 mlx_get_data_addr 함수를 정리했습니다.<br />

cub3d 텍스쳐 부분을 공부하는 분들에게 도움이 되었으면 좋겠습니다. <br />
