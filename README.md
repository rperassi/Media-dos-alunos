# Media-dos-alunos

# ALGORITMO

inicio 

	(Rotina de entrada)

	para a de 1 até 6 passo 1 faça
		escreva "DIGITE O NUMERO DE PESSOAS DA SALA: " 
		leia s_quanti[a,1]
		s_quanti[a,2] = a
		sm_contagem++
	fim_para


	media = sm_contagem / 6


	( Rotina de saida )

	escreva media

	para a de 1 até 6 passso 1 faça
		se (s_quanti[a,1] > media)
			escreva s_quanti[a,0], s_quanti[a,1]
		fim_se
	fim_para

	para a de 1 até 6 passso 1 faça
		se (s_quanti[a,1] < media)
			escreva s_quanti[a,0], s_quanti[a,1]
		fim_se
	fim_para
fim

# FLUXOGRAMA

