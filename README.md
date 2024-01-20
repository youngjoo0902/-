
	<table style="border-collapse: collapse; width: 100%; height: 623px;" border="1" data-ke-style="style12">
		<tbody>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;"><b>HTML 태그</b></td>
		<td style="width: 39.031%; height: 20px; text-align: center;"><b>암묵적 기본 역할 (role="")</b></td>
		<td style="width: 33.3333%; height: 20px; text-align: center;"><b>적용 가능한 역할 (role="")</b></td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;a href=""&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">role="link"</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">button, checkbox, menuitem, menuitemcheckbox, menuitemradio, option, radio, switch, tab</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;a&gt; (href 속성 없이)</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">x</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">어떤 role이든 적용 가능</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;article&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">role="article"</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">application, document, feed, main, none, presentation, region</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;aside&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">role="complementary"</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">feed, none, note, presentation, region, search</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;header&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: left;"><u>article, aside, main, nav, section </u><br><u>태그</u>의 자손 요소이거나<br><br><u><b>role</b>=article, complementary, main, navigation, region</u>을 사용한 태그의 자손일 경우엔 암묵적 역할이 따로 없고<br><br><b>해당 요소들의 자손요소가 아닐 경우엔role="banner"</b>이다.</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">group, none, presentation</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;footer&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: left;"><u>article, aside, main, nav, section</u><br><u>태그</u>의 자손 요소이거나<br><br><u><b>role</b>=article, complementary, main, navigation, region</u>을 사용한 태그의 자손일 경우엔 암묵적 역할이 따로 없고<br><br><b>해당 요소돌의 자손요소가 아닐 경우엔 role="contentinfo"이다.</b></td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">group, none, presentation</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;section&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: left;">accessible name을 가지고 있다면<br><b>role="region"</b><br><br>그렇지 않다면 역할이 따로 없다.</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">alert, alertdialog, application, banner, complementary, contentinfo, dialog, document, feed, log, main, marquee, navigation, none, note, presentation, search, status, tabpanel</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;button&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">role="button"</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;">checkbox, link, menuitem, menuitemcheckbox, menuitemradio, option, radio, switch, tab</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; height: 20px; text-align: center;">&lt;div&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: center;">x</td>
		<td style="width: 33.3333%; height: 20px; text-align: center;"><span style="color: #333333;">어떤 role이든 적용 가능</span></td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;dl&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">x</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">group, list, presentation, none</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;dt&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="term"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">listitem</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;dd&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="definition"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">x</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;fieldset&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="group"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">none, presentation, radiogroup</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;form&gt;</td>
		<td style="width: 39.031%; height: 20px; text-align: left;"><span style="color: #333333;">accessible name을 가지고 있다면</span><br><b>role="form"</b><br><br><span style="color: #333333;">그렇지 않다면 역할이 따로 없다.</span></td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">search, none, presentation</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;h1&gt; ~ &lt;h6&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="heading"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">none, presentation, tab</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;img alt="텍스트"&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="img"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">button, checkbox, link, menuitem, menuitemcheckbox, menuitemradio, option, progressbar, scrollbar, separator, slider, switch, tab, treeitem</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;img alt=""&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">x</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">x</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;img&gt; (alt 속성 없이)</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="img"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">x</td>
		</tr>
		<tr style="height: 21px;">
		<td style="width: 27.6356%; text-align: center; height: 21px;">&lt;ul&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 43px;" rowspan="2">role="list"</td>
		<td style="width: 33.3333%; text-align: center; height: 43px;" rowspan="2">directory, group, listbox, menu, menubar, none, presentation, radiogroup, tablist, toolbar, tree</td>
		</tr>
		<tr style="height: 22px;">
		<td style="width: 27.6356%; text-align: center; height: 22px;">&lt;ol&gt;</td>
		</tr>
		<tr style="height: 80px;">
		<td style="width: 27.6356%; text-align: center; height: 80px;">&lt;li&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 80px;">role="listitem"</td>
		<td style="width: 33.3333%; text-align: center; height: 80px;">menuitem, menuitemcheckbox, menuitemradio,option, none, presentation, radio, separator, tab, treeitem</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;nav&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="navigation"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">menu, menubar, tablist</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;svg&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="graphics-document"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;"><span style="color: #333333;">어떤 role이든 적용 가능</span></td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;input type="button"&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="button"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">link, menuitem, menuitemcheckbox, menuitemradio, option, radio, switch, tab</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;input type="checkbox"&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="checkbox"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">button(사용할 경우 aria-pressed 함께 사용), menuitemcheckbox, option, switch</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;input type="radio"&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="radio"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">menuitemradio</td>
		</tr>
		<tr style="height: 20px;">
		<td style="width: 27.6356%; text-align: center; height: 20px;">&lt;input type="text"&gt;</td>
		<td style="width: 39.031%; text-align: center; height: 20px;">role="textbox"</td>
		<td style="width: 33.3333%; text-align: center; height: 20px;">combobox, searchbox, spinbutton</td>
		</tr>
		</tbody>
		</table>
