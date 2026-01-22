local ID_AUTORIZADO = 1234567890 -- Substitua pelo ID do seu jogo

if game.PlaceId ~= ID_AUTORIZADO then
    warn("Aviso: Este script não tem permissão para rodar neste jogo.")
    return -- Interrompe a execução do restante do script
end

-- O restante do seu código vem aqui embaixo:
print("Script carregado com sucesso no jogo correto!")
