# muralcodopesquisa
# para realizar pesquisa de mercado
<!DOCTYPE html>
 
<html>
 <head>
 <title> MuralNatural </title>
 <meta name="description" content="formulário em HTML">
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8"> 
 </head>

 <body>
  <h1> Bem vindo ao Mural Natural - Realizando uma pesquisa de mercado </h1>
  <h2> Preencha o formulário abaixo para participar da pesquisa do Mural Natural de Codó</h2><br />

<form method="post" name="contact" >

<!-- DADOS PESSOAIS-->
<fieldset>
 <legend>Dados Pessoais</legend>
 <table cellspacing="9">
  <tr>
   <td>
    <label for="nome">Nome: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
   <td>
    <label for="sobrenome">Sobrenome: </label>
   </td>
   <td align="left">
    <input type="text" name="sobrenome">
   </td>
    <td>
    <label for="sobrenome">Idade:   </label>
   </td>
   <td align="left">
    <input type="text" name="Idade">
   </td>
  
   
 </table>
</fieldset>

<br />
<!-- ENDEREÇO -->
<fieldset>
 <legend>Dados de Endereço</legend>
 <table cellspacing="9">

  <tr>
   <td>
    <label for="rua">Rua:</label>
   </td>
   <td align="left">
    <input type="text" name="rua">
   </td>
   <td>
    <label for="numero">Numero:</label>
   </td>
   <td align="left">
    <input type="text" name="numero" size="4">
   </td>
  </tr>
  <tr>
   <td>
    <label for="bairro">Bairro: </label>
   </td>
   <td align="left">
    <input type="text" name="bairro">
   </td>
  </tr>
  <tr>
   <td>
    <label for="estado">Estado:</label>
   </td>
   <td align="left">
    <select name="estado"> 
    <option value="ac">Acre</option> 
    <option value="al">Alagoas</option> 
    <option value="am">Amazonas</option> 
    <option value="ap">Amapá</option> 
    <option value="ba">Bahia</option> 
    <option value="ce">Ceará</option> 
    <option value="df">Distrito Federal</option> 
    <option value="es">Espírito Santo</option> 
    <option value="go">Goiás</option> 
    <option value="ma">Maranhão</option> 
    <option value="mt">Mato Grosso</option> 
    <option value="ms">Mato Grosso do Sul</option> 
    <option value="mg">Minas Gerais</option> 
    <option value="pa">Pará</option> 
    <option value="pb">Paraíba</option> 
    <option value="pr">Paraná</option> 
    <option value="pe">Pernambuco</option> 
    <option value="pi">Piauí</option> 
    <option value="rj">Rio de Janeiro</option> 
    <option value="rn">Rio Grande do Norte</option> 
    <option value="ro">Rondônia</option> 
    <option value="rs">Rio Grande do Sul</option> 
    <option value="rr">Roraima</option> 
    <option value="sc">Santa Catarina</option> 
    <option value="se">Sergipe</option> 
    <option value="sp">São Paulo</option> 
    <option value="to">Tocantins</option> 
   </select>
    <td>
    <label for="nome">Nome: </label>
   </td>
 
   </td>
  </tr>
  <tr>
   <td>
    <label for="cidade">Cidade: </label>
   </td>
   <td align="left">
    <input type="text" name="cidade">
   </td>
  </tr>
  <tr>
   <td>
    <label for="cep">CEP: </label>
   </td>
   <td align="left">
    <input type="text" name="cep" size="5" maxlength="5"> - <input type="text" name="cep2" size="3" maxlength="3">
   </td>
  </tr>
 </table>
</fieldset>
<br />

<!-- EMPREENDIMENTOS --!>
<fieldset>
 <legend>Qual empreendimento você gostaria aqui?</legend>
 <table cellspacing="12">
  <tr>
    <label for="estado">Tipos de empreendimentos :</label>
   </td>
   <td align="left">
    <select name="estado"> 
    <option value="ac">Restaurante</option>
    <option value="al">Lanchonete</option>
    <option value="am">Churrascaria</option>
    <option value="ap">Pizzaria</option>
	<option value="ba">Padaria</option>
    <option value="ce">Mercadinho</option>
    <option value="df">Escritório de advogacia</option>
    <option value="es">Dentista</option>
    <option value="go">Clinica</option>
    <option value="ma">Seguradora</option>
    <option value="mt">Banco</option>
    <option value="ms">Academia</option>
    <option value="mg">Escola infantil</option>
    <option value="pa">Locadora de veiculos</option>
    <option value="pb">Imobiliaria</option>
    <option value="pr">Cartório</option>
    <option value="pe">Correios</option>
    <option value="pi">Casa Noturna</option>
    <option value="rj">Casa de construção</option>
    <option value="rn">Salão de Beleza</option>
    
   </select>
    <td>
    <label for="nome">Outro Empreendimento: </label>
   </td>
   <td align="left">
  
    <input type="text" name="email">
   </td>
  
 </table>
</fieldset>
<br />


<input type="submit">
 
<input type="reset" value="Limpar">

</form>

 </body>
</html>
