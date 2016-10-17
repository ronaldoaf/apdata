# apdata
apdata


```sql
--Lista de eventos
select *  from EventosPonto;
```


|EAP_Cd|EAP_VlnCalculo1         |EAP_D1sEventoPonto              |
|---|---|---|
|0|0|Nenhum                          |
|1|0|Horas Normais Trabalhadas       |
|2|0|Permanencia Nâo Autorizada (Seg |
|3|0|Permanencia Nâo Autorizada (Sáb,|
|4|0|Marcação Irregular              |
|5|0|HEX - Hora Extra                |
|6|0|CBH - Crédito B.H.              |
|7|0|SALDO ANTERIOR (+)              |
|8|0|SALDO ANTERIOR (-)              |
|9|NULL                    |CRÉDITO MÊS                     |
|10|NULL                    |DÉBITO MÊS                      |
|11|NULL                    |SALDO FINAL (+)                 |
|12|NULL                    |SALDO FINAL (-)                 |
|13|0|SALDO MENSAL B.H. (+)           |
|14|0|SALDO MENSAL B.H. (-)           |
|15|0|DBH - Débito B.H.               |
|16|0|Atraso Abonado                  |
|17|0|Saída Abonado                   |
|18|0|Atraso (Abono Empresa)          |
|19|0|Saída - (Calculo Abono Empresa) |
|20|0|Acerto BH Crédito               |
|21|0|Acerto BH Débito                |
|22|0|ATO - Atraso de Ônibus          |
|23|0|COP - Consulta Preventiva       |
|24|0|Maternidade                     |
|25|0|Licença Sem Remuneração         |
|26|0|INSS                            |
|27|0|Adicional Noturno               |
|28|0|2o COP do Dia - Consulta Prevent|
|36|36|Horas Extras 60%                |
|40|0|CBH - Crédito B.H. ESPECIAL     |
|41|0|HEX - Hora Extra Dia Livre      |
|50|0|DBHE - Débito B.H - ENTRADA     |
|51|0|DBHE - Débito B.H - Intervalo   |
|52|0|DBHE - Débito B.H - Aus Intermed|
|56|0|CBH - Crédito B.H. Diurno       |
|57|0|CBH - Crédito B.H. Noturno      |
|58|0|CBH - Crédito B.H. Dia Livre    |
|59|0|CBH - Crédito B.H. Sáb/Dom:Feria|
|60|0|DBHS - Débito B.H               |
|61|0|É Dia de Recesso                |
|70|3293|Horas Extras 75%                |
|78|7821|Débito de Banco de Horas        |
|79|0|Total de Horas Realizadas no Dia|
|99|0|Férias                          |
|100|0|Lançamento Diário  - Crédito B.H|
|101|0|Lançamento Diário  - Débito B.H.|
|120|220|Lançamento - Horas Extras 55% DE|
|121|36|Lançamento - Horas Extras 60% DE|
|122|1636|Lançamento - Horas Extras 100%  |
|123|0|Lançamento - Horas Extras 75%   |
|200|0|MAI - Marcação Irregular        |
|201|0|ATE - Atividade Externa         |
|202|0|TRN - Treinamento / Curso       |
|203|0|AFM - Afastamento Militar       |
|204|0|CRE - Reuniões/Atividades do CRE|
|205|0|AUL - Acompanhamento Menor 1    |
|206|0|AUL - Audiência/Judiciário/Sindi|
|207|0|AUL - Doação de Sangue          |
|208|0|AUL - Licença Paternidade       |
|209|0|AUL - Licença Nojo              |
|210|0|AUL - Licença Gala              |
|211|0|FPA - Falta Parcial             |
|212|5204|LNR - Licença Não Remunerada    |
|213|0|ABM - Abono Médico (DIA)        |
|214|0|ABE - Abono Empresa             |
|215|0|Total Abono Empresa             |
|216|0|ABONO FINAL DE ANO              |
|217|0|AUL - Licença Adoção            |
|218|0|ABME - Abono Médico (ENT)       |
|219|0|ABMS - Abono Médico (SAÍ)       |
|220|220|Horas Extras 55%                |
|221|0|FISE - Fisioterapia (ENT)       |
|222|0|FISS - Fisioterapia (SAÍ)       |
|223|0|Afastada em Maternidade         |
|224|0|Auxílio-Doença                  |
|225|0|Auxílio-Doença até 15 Dias      |
|226|0|Ajuda Pecuniária                |
|227|0|AUL - Acompanhamento Menor 2    |
|228|0|AUL - Acompanhamento Menor 3    |
|229|0|AUL - Acompanhamento Menor 4    |
|230|0|AUL - Acompanhamento Menor 5    |
|231|0|AUL - Acompanhamento Menor 6    |
|232|0|Tratamento Manhã                |
|233|0|Tratamento Tarde                |
|250|0|Hrs Faltantes p/ 11 hrs - Interj|
|260|0|COP - Consulta Preventiva       |
|261|0|AUL - Acompanhamento Menor      |
|262|0|AUL - Audiência/Judiciário-teste|
|263|0|AUL - Doação de Sangue          |
|264|0|AUL - Licença Paternidade       |
|265|0|AUL - Licença Nojo              |
|266|0|AUL - Licença Casamento         |
|267|0|AUL - Licença Adoção            |
|268|0|AUL - Justiça Eleitoral         |
|300|0|Cálculo - Inicializa Diário     |
|301|0|Cálculo - Marcações Inconsistent|
|302|0|Cálculo - Atrasos               |
|303|0|Cálculo - Saídas Antecipada     |
|304|0|Cálculo - Faltas Ponto          |
|305|0|Cálc Hora Extra Dia Normal - Rig|
|306|0|Cálc HE Sáb, DSR, Folga e Feriad|
|307|0|Cálculo - Horas Normais Trabalha|
|308|0|Cálculo - Inicializa Mensal     |
|309|0|Cálculo - Inicializa Diario - Me|
|310|0|Cálculo - Adicional Noturno     |
|311|0|Cálculo - Sumariza HE e Adc Notu|
|312|0|Cálculo - Sumariza BH           |
|313|0|Cálculo - Horário Móvel         |
|314|0|Cálculo - Sobre-aviso           |
|315|0|Cálculo - Exibe Eventos Sumariza|
|316|0|Cálculo - Refeição - Diário     |
|317|0|Cálculo - Contabiliza Banco Hora|
|318|0|Cálculo - Zera Banco de Horas   |
|319|0|Cálculo - Abono Empresa         |
|320|0|Cálculo - Horas Trabalhas Estagi|
|321|0|Cálc Verifica Ataso/Saída (Abono|
|323|0|Cálculo - Sumariza Eventos Estag|
|324|0|Cálculo - Contabiliza Eventos Es|
|325|0|Cálculo - Interjornada          |
|326|0|Horas Normais                   |
|327|0|LPC III - Inicializa Diário     |
|328|0|LPC III - Crédito               |
|329|0|---------- LPC II ----------    |
|330|0|Débito - Ausências              |
|331|0|Ajusta Débitos                  |
|332|0|Créditos com Quebra às 00h00 -A |
|333|0|Teste 6 horas Drs/Sab/Fer (NOVO)|
|334|0|Datas Especias - Recesso        |
|335|0|INTEGRAÇÃO - SERVIÇO MÉDICO     |
|336|0|Total de Horas Trabalhadas      |
|413|3426|Adicional Noturno 30%           |
|414|7821|Débito de Banco de Horas        |
|415|0|Horas Trabalhadas Estagiário    |
|416|0|Extensão Adc. Noturno 30%       |
|417|0|Extensão Adc. Noturno 30% - 100%|
|418|0|Redução Adc. Noturno 30%        |
|419|0|Redução Adc. Noturno 30% - 100% |
|504|0|Hrs Trabalhadas Estagiários     |
|506|0|Hrs Trabalhadas Estagiário - 06 |
|508|0|Hrs Trabalhadas Estagiário - 08 |
|721|7213|Refeição Sem Subsidio           |
|1259|1259|Adicional Sobre-aviso           |
|1636|1636|Horas Extras 100%               |
|1648|1648|Adicional Noturno 30% - 100%    |
|1673|1673|Horas Extras B.H. 60%           |
|1697|1697|Horas Extras B.H. 100%          |
|1698|3402|Horas Extras B.H. 75%           |
|5010|5010|ANP - AUS. NECES. PARTICULAR    |
|5137|5137|FAL - Falta Integral            |
|5149|5149|Falta Parcial                   |
|5150|5150|SAN - Saída Antecipada          |
|5174|5174|ATR - Atrasos                   |
|5204|5204|LNR - Licença Não Remunerada    |
|5205|0|ATO - Atraso de Ônibus          |
|5206|0|Almoço                          |
|5207|0|Jantar                          |
|5208|0|Ceia                            |
|5209|0|Desjejum                        |
|5210|0|Teste 6 horas Entrada           |
|5211|0|Agrupa Credito e Debito de Banco|
|5212|0|ABE - RH                        |
|5253|5253|Refeição Subsidiada             |
|5306|0|Almoço Terceiros                |
|5307|0|Janta Terceiros                 |
|5308|0|Ceia Terceiros                  |
|5309|0|Desjejum Terceiros              |
|5310|0|Data Especial - Quarta de Cinzas|
|5312|0|Data Especial - Natal e Ano Novo|
|5313|0|AUL - Justiça Eleitoral - TRE   |
|5314|0|CFA - Coletor fora do ar        |
|5315|0|Abono Medico                    |
|5316|0|Teste 6 horas Saida             |
|5317|0|Teste 6 horas Drs/Sab/Fer (ANTIG|
|5318|0|Cálculo de Desconto de Refeição |
|5319|0|Sumariza Refeição               |
|5320|0|Exibe Refeição                  |
|5321|0|Contabiliza Banco de Horas - Rig|
|5322|0|Jornada 06 horas - Desconto 01:0|
|5323|0|Abate HEX de DBH                |
|5324|0|Inicia Variaveis BH e HE        |
|5325|5526|Horas Ausência Estagiário       |
|5326|0|AUL - Licença Amamentação       |
|5327|0|APR - Abono Perícia  INSS / Reto|
|5328|0|Soma HEX / DBH                  |
|5329|0|Contabiliza HEX x DBH Mês       |
|5330|0|Total HEX Realizados Mês        |
|5331|0|Total DBH Realizados Mês        |
|5332|0|AUL - Vestibular / Provas       |
|5333|0|coe                             |
|5334|0|AUL - Atividade Sindical        |
|5335|0|Férias                          |
|5336|0|FER - Férias                    |
|5337|0|ABM - Manhã/ Tarde              |
|5338|0|ABM - Manhã / Tarde             |
|5339|0|ABM - Manhã / Tarde             |
|5340|0|AUL - Acompanhamento dos pais   |
|5341|0|Reunião do Sistema Agenda em Tab|
|5342|0|FERIADO TABOÃO DA SERRA         |
|5343|0|AUL - Acompanhamento Gestante   |
