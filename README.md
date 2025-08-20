1. FrameLayout

O que é: Layout simples que empilha views; a última adicionada aparece por cima das anteriores.
GeeksforGeeks
androidframework.com

Quando usar:

Para sobrepor elementos (como botão sobre imagem ou animações).

Placeholder para fragments ou componentes que mudam.

Quando só um elemento precisa estar visível por vez.
thiagocury.eti.br
bomberbot.com

2. LinearLayout

O que é: Organiza Views em sequência, em linha horizontal ou vertical.
GeeksforGeeks
DigitalOcean

Quando usar:

Layouts simples, como menus ou listas básicas.

Quando não existe necessidade de posicionamento complexo entre elementos.

Atenção: aninhamentos profundos e uso de layout_weight podem afetar a performance.
GeeksforGeeks
Stack Overflow
DigitalOcean

3. RelativeLayout

O que é: Permite posicionar views em relação entre si ou em relação ao container pai.
GeeksforGeeks
androidframework.com

Quando usar:

Para cenários que requerem posicionamento relativo simples (por exemplo, texto abaixo de outro ou alinhado à borda).

Observações:

Foi muito popular, mas hoje tende a ser substituído por ConstraintLayout.

Pode impactar performance devido à dupla medição necessária.
GeeksforGeeks
Stack Overflow
Stack Overflow em Português
androidframework.com

4. ConstraintLayout

O que é: Layout avançado baseado em restrições entre elementos, ideal para telas complexas com hierarquia plana.
Codeplayon
androidframework.com
Stack Overflow em Português

Quando usar:

Telas com múltiplos alinhamentos, restrições dinâmicas, guidelines, chains e layouts responsivos.
Codeplayon
androidframework.com
Medium
Stack Overflow
Stack Overflow em Português

Observações:

Facilita performance ao reduzir níveis de aninhamento.

Pode ser desnecessariamente complexo para layouts simples; nesses casos, prefira FrameLayout ou LinearLayout.
ICHI.PRO
Stack Overflow em Português
Medium

5. RecyclerView

O que é: Componente para exibição eficiente de listas grandes ou dinâmicas, reutilizando views via ViewHolder. (Não é apenas um layout, mas um container altamente performático.)

Quando usar:

Listas ou grades com muitos itens.

Para scroll suave, performance e flexibilidade na criação de layouts customizados de item.
